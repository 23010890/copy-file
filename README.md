# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Start the program

## Step 2:
Open the file f1 in read mode

## Step 3:
Open the file f2 in write mode

## Step 4:
Copy the contents using write() with the for loop

## Step 5:
End the program
## PROGRAM:
```python
##Developed by: DHARSHINI S
##Register number:23010890

with open('f1.txt','r') as f1:
    with open('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![output](./FILE%201.png)
![output](./FILE%202.png)
![output](./FILE%201%20COPIED%20TO%20FILE%202.png)
## RESULT:
Thus the program is written to copy the contents from one file to another file.