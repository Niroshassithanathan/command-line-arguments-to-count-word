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
```
##Developed by :NIROSHA.S
##Register number :22009078

import sys

with open(sys.argv[1],'r') as f:
    num_words =0
    for i in f:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
![](command1.jpg)
![](command2.jpg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
