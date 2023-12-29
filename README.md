# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it

### Step 2:
Open the text1.txt file in read mode
 
### Step 3:
Create a copy.txt file using write mode

### Step 4: 
Copy the content of text1.txt file to copy.txt using write function:

### PROGRAM:
Program for copying the contents from one file to another file
Developed by: karthi keyan k
RegisterNumber: 23013936

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)

### OUTPUT:
![image](https://github.com/Karthi051/copy-file/assets/148327224/15170fe0-54a2-49b0-ac59-b780d6fa8095)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
