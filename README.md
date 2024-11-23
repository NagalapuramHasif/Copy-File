# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Import the necessary library to handle file uploads.
### Step 2: 

Create a function called copy_file that takes two parameters: source and destination.

### Step 3: 

Inside the function, open the source file in read mode and read its contents.

### Step 4:  

Open the destination file in write mode and write the contents read from the source file into it.

### Step 5: 

Print a success message indicating that the contents have been copied.

### Step 6: 

Handle any errors that may occur, such as file not found or other exceptions.

## PROGRAM:
```
def copy(fname,newfile):
    with open(fname) as fp:
        with open(newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("textfile1.txt","textfile2.txt")
```

### OUTPUT:

![image](https://github.com/user-attachments/assets/c6b17605-a520-433c-a600-72d0ad4f06a2)

![image](https://github.com/user-attachments/assets/af5e0648-c50c-468c-ae73-5bc71f5afb4d)


## RESULT:
Thus the program is written to copy the contents from one file to another file..
