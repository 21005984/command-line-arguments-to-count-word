# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2:
open file using open().  
 
### Step 3: 
use for loop

### Step 4: 
use len to count number of words 

### Step 5: 
give print
## PROGRAM:
```
### NAME:MEIYARASI.V
### REGISTER NUMBER:21005984
import sys
count(0)
with open (sys.arv[1],'r') as f:
    for line in f:
    word=line.split()
    count+=len(word)
print('word count in file =' ,count)
```

### OUTPUT:
![Output](.//C1.jpg)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
