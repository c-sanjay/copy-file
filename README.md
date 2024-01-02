# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
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
```py
#PROGRAM: Copy - File
#Developed by : SANJAY C
#Reg no : 212223240150
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:
![](./copyfile.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.