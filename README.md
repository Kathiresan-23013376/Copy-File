# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.

### Step 2: 
 Print the number of contents to be displayed using df.head().


### Step 3: 
The number of rows returned is defined in Pandas option settings.

### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5: 
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
`````
#To write a python program for reading content from a CSV file.
#Developed by: KATHIRESAN K
#Register Number: 212223110021

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```````

### OUTPUT:

![image](https://github.com/Balaji-Jothiramalingam/Copy-File/assets/114234865/f2370406-5c86-4f2b-9a73-810de48fa8b5)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
