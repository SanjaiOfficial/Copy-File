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
![Screenshot 2024-05-11 190709](https://github.com/SanjaiOfficial/Copy-File/assets/151763180/c4b5d36d-1d45-4474-998e-89a705b66ba1)

![Screenshot 2024-05-11 190729](https://github.com/SanjaiOfficial/Copy-File/assets/151763180/f35b878e-6040-48b0-b280-f66dc78a49f8)

![image](https://github.com/SanjaiOfficial/Copy-File/assets/151763180/fee824ae-13ef-4492-8c01-cf85db1d1ce9)


## RESULT:
Thus the program is written to copy the contents from one file to another file executed successfully.
