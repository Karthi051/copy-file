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
![image](https://github.com/Karthi051/copy-file/assets/148327224/c6a64f67-1625-45f8-af64-7c203adf073e)
![image](https://github.com/Karthi051/copy-file/assets/148327224/da86f040-04d0-4ab0-b94a-686dbbc9a7ea)
![image](https://github.com/Karthi051/copy-file/assets/148327224/ef3bba88-0f97-4cfd-befb-d5e2018d3255)







## RESULT:
Thus the program is written to copy the contents from one file to another file.
