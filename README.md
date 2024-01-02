# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
1,PC
2,Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
From shutil import copy file
### Step 2:
From sys import exit
### Step 3:
Getting input for source file
### Step 4:
Getting input for target file
### Step 5:
Giving condition for files
### Step 6:
Getting statement from the user to print or not want to print
## PROGRAM:
```
def copy(fname,newfile):
  with open(fname,'r')as fp:
    with open(newfile,'w')as fp1:
      data1=fp.read()
      fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname,newfile)
```
### OUTPUT:
![image](https://github.com/Gokkul-M/copy-file/assets/144870543/6da85713-ac54-45ce-bb4a-df99084942f1)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
