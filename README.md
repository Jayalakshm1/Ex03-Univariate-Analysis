# Ex03-Univariate-Analysis
#DEVELOPED BY:JAYALAKSHMI M
#REGISTER NUMBER:212221040066
# AIM
To detect the Univariate Analysis by using default functions.
# ALGORITHM
1.Import pandas(),numpy()and seaborn() for a required detection.
2.use the head()
3.The information and is null function.
4.Use the describe function.
5.Figure the boxplot.
6.plot the countrplot,Displot,Histoplot.
7.Print the program.
# PROGRAM
```
import pandas as pd
import numpy as np
import seaborn as sns
data=pd.read_csv('SuperStore.csv')
data
data.head()
data.info()
data.describe()
data.isnull().sum()
data.dtypes
data['Postal Code'].value_counts()
sns.boxplot(x='Postal Code', data=data)
sns.countplot(x='Postal Code',data=data)
sns.distplot(data["Postal Code"])
sns.histplot(x='Postal Code',data=data)
```
# OUTPUT
![EX03-UNIVARIATE-ANALYSIS](ex3(1).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(2).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(3).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(4).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(5).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(6).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(7).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(8).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(9).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(10).png)
![EX03-UNIVARIATE-ANALYSIS](ex3(11).png)
# RESULT
Hence the univariate analyses is verified.

