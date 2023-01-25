# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Use open function to open the file in which we want to copy from and access it in read mode.

### Step2:

Read the file and store in a variable.
### Step3:

Now create a new file in which we want to paste the content using write access mode.
### Step 4:

Use write function to copy the read file that has been stored in the variable.
### Step 5:

The content in the original file will be copied in the new file.
### Step 6:

End the program.



## PROGRAM:
```python
To write a program for copying the contents from one file to another file.
Developed by: Jivan Karthec.B.S
RegisterNumber: 22004763

with open("myfile.txt","r") as fp:
    x = fp.read()
with open("data3.txt","w") as fp1:
    fp1.write(x)
```

### OUTPUT:
![13](https://user-images.githubusercontent.com/121165867/214643810-07e9f22b-1a89-4f58-b8e2-113305e1906d.png)

![14](https://user-images.githubusercontent.com/121165867/214643883-e6036302-d72c-4b71-aa3f-4de6d6017cb1.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
