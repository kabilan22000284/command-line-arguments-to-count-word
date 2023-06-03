# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module

### Step 2:
Open the file with sys.argv[1]

### Step 3:
Use the for loop to select the content in file

### Step 4:
Use split function to to separate the file content into words or strings

### Step 5:
Count the length of the words using len

### Step 6:
Print the number of words

## PROGRAM:
'''
Program for getting the word count from the contents of a file using command line arguments
Developed by: kabilan V
RegisterNumber: 212222100018
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("Number of words in a file",count)
```
### OUTPUT:
![image](https://github.com/kabilan22000284/command-line-arguments-to-count-word/assets/123469171/1bbe59aa-80e1-47be-90e8-77c18e1540ab)
![image](https://github.com/kabilan22000284/command-line-arguments-to-count-word/assets/123469171/e26f1ce1-34ff-4a1f-b769-7f0bb62d0edd)
![image](https://github.com/kabilan22000284/command-line-arguments-to-count-word/assets/123469171/84d6acba-6885-41ae-b9e4-90a80db759c0)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
