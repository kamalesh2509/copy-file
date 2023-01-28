# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode. 
### Step 2: 
 Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode. 
### Step 4:  
Use write function to copy the read file that has been stored in the variable. 
### Step 5: 
The content in the original file will be copied in the new file. 
### Step 6: 
The End. 
## PROGRAM:
```
with open("file.txt") as fp:
    with open("fire2.txt","w") as fp1:
        line= fp.read()
        fp1.write(line)
```

### OUTPUT:
![file1](https://user-images.githubusercontent.com/93427303/153134435-66195353-cebe-4b4c-a682-1a2c8fbde77e.JPG)

![file2](https://user-images.githubusercontent.com/93427303/153134513-52538721-a6e7-433b-be36-15e9f32e05eb.JPG)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
