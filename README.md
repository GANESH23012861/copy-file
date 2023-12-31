# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
Get the file name and location from the user.
### Step 2: 
Give a new file name to create a copy of a file content.
### Step 3:
 Read the file and close the file.
### Step 4: 
Now write the content in the new file.
### Step 5:
 When done print"File copied successfully".
### Step 6: 
End of the program
## PROGRAM:
```
# To write a program for coping the contents from one to another file.
# Developed by : Selvaganesh
#RegisterNumber:23012861
with open("file.txt","r") as f:
    x=f.read()
with open("file1.txt","w") as f1:
    f1.write(x)
```
### OUTPUT:
![Screenshot 2023-12-31 113721](https://github.com/GANESH23012861/copy-file/assets/147139861/0c73db94-16ca-405c-9ad8-8a413a545161)
![Screenshot 2023-12-31 113834](https://github.com/GANESH23012861/copy-file/assets/147139861/fd3a68a4-64a9-4ad8-99be-fa8da77f4855)
![Screenshot 2023-12-31 113947](https://github.com/GANESH23012861/copy-file/assets/147139861/71949f0e-72c9-4eef-8885-0640b7e3bafd)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
