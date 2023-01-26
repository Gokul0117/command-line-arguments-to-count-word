# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2: 
Pass the filename as the first argument after the name of script.Open the file as sys.argv[1]


 
### Step 3: 
Read the file using read() method

### Step 4:  
Use split() method to split the file content into words.


### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file create

## PROGRAM:
```
Developed by: Gokul J
Register number:22009062

import sys
fp=open(sys.argv[1],"r")
d={}
for i in fp:
    for w in i.split():
        if w not in d.keys():
            d[w]=1
        else:
            d[w]+=1
print(d)

### OUTPUT:
![Screenshot from 2023-01-26 17-22-38](https://user-images.githubusercontent.com/121165938/214828889-4a4768e0-3a64-4811-9078-09817981e9df.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
