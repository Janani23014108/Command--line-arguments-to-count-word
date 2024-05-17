# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Import sys module to use command line arguments.

### Step 2: 

Create a file pointer and open the file which is passed in command line.

### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.

### Step 5: 
Sum the number of words in each line.
### Step 6:
Display the total words in the file.



## PROGRAM:
```
Developed by: J.JANANI
Register no: 212223230085
import sys
fp=open(sys.argv[1])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()
```
### OUTPUT:

![13df9583-f3e4-4706-b1d9-e812d63b87f8](https://github.com/Janani23014108/Command--line-arguments-to-count-word/assets/146822085/8d7d024e-d8ed-4ce4-b57d-2a377ab59ded)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
