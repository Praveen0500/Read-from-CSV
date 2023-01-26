# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.

### EQUIPMENTS REQUIRED:
PC Anaconda - Python 3.7

## ALGORITHM:
### Step 1:
Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
'''
Developed By : Praveen s

Referance No. : 22009060
'''
import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```

## OUTPUT:
![P6 pra](https://user-images.githubusercontent.com/120218611/214782232-2ec9ba0e-4cf7-4ee0-82a8-336301b3c5f0.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
