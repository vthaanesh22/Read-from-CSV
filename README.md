# Read-from-CSV

## AIM:
To write a program to read a csv file.
## ALGORITHM:
## Step 1:
Import pands module as pd.
## Step 2:
Read a csv file name cars.csv.
## Step 3:
Print the first five rows and last five rows.
## Step 4:
Print the length of the rows and columns.
## Step 5:
End the program.
## PROGRAM:
## DEVELOPED BY:V.THAANESH
## REG.NO: 23003843
```
import pandas as pd
df = pd.read_csv("/content/drive/MyDrive/Colab Notebooks/cars (1).csv")
print(df.head())
print(df.tail())
print("Rows", len(df.axes[0]))
print("Columns", len(df.axes[1]))
```

## OUTPUT:
![output](/Screenshot%202023-07-31%20104054.png)
![output](/Screenshot%202023-07-31%20104309.png)
## RESULT:
Thus the program is written to read a csv file.