# Read-from-CSV

## AIM:
To read a csv file and access the data

## ALGORITHM:
```
Step 1:
Start python

Step 2:
Import the required csv file.

Step 3:
Import pandas

Step 4:
Read the csv file by using df.read.

Step 5:
Display the Columns.

Step 6:
Display the Rows.

Step 7:
End the program
```
## PROGRAM:
~~~
#Developed by : D. vishnu vardhan reddy
#Reference Number : 21005311
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
~~~

## OUTPUT:-
![csv](https://user-images.githubusercontent.com/94175324/153898061-ae108bbb-bbed-4ab6-a4f8-34c8258e4232.png)


## RESULT:
Therefore the program is successfully executed to read csv file and access the data in it.
