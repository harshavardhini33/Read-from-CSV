# Read-from-CSV

## AIM: 
To write a python program to read data from CSV files.

## ALGORITHM:
### Step 1:
Start the python.

### Step 2:
Import pandas.

### Step 3:
Mention the CSV file which is to be read.

### Step 4:
Read the contents of the CSV file using df.read function

### Step 5:
End the program.

## PROGRAM:
#NAME : HARSHAVARDHINI M
#REG NO : 212221240015
~~~
import pandas as pd
df= pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
~~~

## OUTPUT:
![DOC](https://user-images.githubusercontent.com/93427208/153541366-7a25e28b-8b92-4361-99e7-c5585032ec81.png)

![DOC](https://user-images.githubusercontent.com/93427208/153541394-15734c53-e90e-4d97-95ac-024266017dfe.png)



## RESULT:
A python program to read data from CSV files has been created successfully.
