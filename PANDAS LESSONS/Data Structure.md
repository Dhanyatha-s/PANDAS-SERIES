### DATA STRCUTURE IN PANDAS
| SERIES | DATAFRAME | ACESSING DATA |
---------|-----------|----------------|
| 1D Labled Array | 2D Labled Data | Can Acess indivisual rows and column using labled or indicies |
| Lables are known as <b>Index<b> | Similar to Tables | |
| Creating Series | Creating DataFrame | Accessing Data|
|s=pd.Series([1,2,3,4,5]) <n/> print(s) | data = {'Name':['john','mary'], <n/> 'Age':[28,34]} <n/> df = pd.DataFrame(data) <n/> print(df) | print(df.iloc[0]) to access a first <b>row</b> by index. </n>print(df['Name'] Access the column|

