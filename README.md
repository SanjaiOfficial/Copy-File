# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

### Step 2:
Using keyword "with" to open the requied file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'W' which is used to write only.

### Step 5:
The four function is used to take each line from the main file.

## PROGRAM:
```
#Program for copying the contents from one file to another file
#Developed by: SANJAI L
#RegisterNumber: 212223230184
with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("file.txt",'w') as fp1:
    fp1.write(msg1)

```
### OUTPUT:
![image](https://github.com/SanjaiOfficial/Copy-File/assets/151763180/293d1cb9-d247-4091-ab77-b20c61381ab7)



## RESULT:
Thus the program is written to copy the contents from one file to another file executed successfully.
