# GDrive Folder Size Calculator

This is a simple yet only known effective method to calculate google drive folder size using Python.
Works for both gdrive file and folder. Uses Drive Api v3.

## Also calculates total number of files and folders inside whole tree

It returns a dict contains name, size, size in bytes, total number of files and total number of folders
of the given gdrive file/folder's link/fileID. 

The keys in the dict are name, size, bytes, files and folders.

## All you need to do is this:
1) ```pip3 install -r requirements.txt```
2) Create a **service** to pass to the GoogleDriveSizeCalculate class. (Notes to create are given inside the bottom of the script itself)
3) ```python3 gDrive_calculator.py```
4) On terminal, input the url or fileid of your file/folder on Google Drive (File associated with the account you using OR sharable links ONLY)

## Output Example:
```
Name: Channel Zero (2016) Season 1-4 S01-S04 
Size: 38.25GB
Bytes: 41074136619
Files: 24
Folders: 5

If you want only size in bytes:
print(calculate['bytes'])
```
