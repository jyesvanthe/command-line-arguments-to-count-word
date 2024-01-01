# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys.
### Step 2: 
 open the file and assign it to f1.
### Step 3: 
read the file and assign it to data.
### Step 4:  
split the data(data.split()).
### Step 5: 
print the word count by len(word).
### Step 6: 
close the file f1.
## PROGRAM:
```
#python program for word count
#developed by: Jyesvanthe v
#register number : 23013991

import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is ",len(word))
f1.close()

```

### OUTPUT:

![Alt text](<Screenshot 2024-01-01 135337.png>)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
