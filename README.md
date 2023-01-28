# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:   

Step 1:
import sys

Step 2:
open file using open()

Step 3:
Read the file and save in variable

Step 4:
use for loop

Step 5:
use len to count number of words

Step 6:
display the value using print() function

## PROGRAM:
```py
##Developed by :NIROSHA.S
##Register number :22009078

import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()
```
### OUTPUT:

![output](https://user-images.githubusercontent.com/121418437/215250855-8c423a0d-de70-41e2-8bc2-08d8f262eb81.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
