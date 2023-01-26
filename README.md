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
Open file using open().

Step 3:
Use for loop.

Step 4:
Use len to count number of words

## PROGRAM:
#program is developed: CHANDRU M
# REF.NO: 22009010
import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("program is developed: AJAYASWIN.M")
print("word count in file = ",count)
### OUTPUT:

![5b](https://user-images.githubusercontent.com/118644502/214796539-22753ea3-68c6-4c64-b18e-a626b8b41eec.jpg)
![5b1](https://user-images.githubusercontent.com/118644502/214796559-6b600689-d89e-428b-8372-aa8c3bcebef8.jpg)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
