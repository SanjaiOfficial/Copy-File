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
#Developed by : SANJAI L
#Register No : 212223230184
with open ("text.txt") as fp:
  with open("file.txt","w") as fp1:
    line= fp.read()
    fp1.write(line)
```
### OUTPUT:
![image](https://github.com/SanjaiOfficial/Copy-File/assets/151763180/35bcf9c3-23aa-437c-90ca-ec86cd9d158f)

## RESULT:
Thus the program is written to copy the contents from one file to another file executed successfully.
