# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import pandas as pd.
### Step 2: 
 Read the CSV file using read_csv method.
### Step 3: 
Use head and tail method to get the required contents from the file.
### Step 4:  
Use len() method to get the number of rows and columns.
### Step 5: 
Print the output.
### Step 6: 
End program
## PROGRAM:
```
Developed by:sirisha onteddu
Ref.no:22003264

import pandas as pd
f=pd.read_csv("/content/nba (2).csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/119389139/214853306-83530998-9102-48c7-a501-d52c57e4a110.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
