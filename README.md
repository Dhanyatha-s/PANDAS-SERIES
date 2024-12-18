# PANDAS-SERIES
### I've taken the Titanic dataset just to understand the data and learn the pandas 
### There is new alternative to pandas or may be best library compared to pandas is 'Polars'
#### Here is the Link to have Dataset ["https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"]


## PANDAS

### lOADING THE DATA
##### CSV FILE
```
pd.read_csv()

```
##### EXCEL FILE
```
pd.read_excel()
```

##### JSON FILE
```
pd.read_json()
```
##### SQL DATABASE
```
pd.read_sql()

import sqlite3
conn = sqlite3.connect('database.db')
query = 'SELECT * FROM table_name'
df = pd.read_sql(query, conn)

```
##### HTML FILES
```
pd.read_html()
df = pd.read_html('https://example.com')[0]  # Returns a list of DataFrames
```
##### TEXT FIELS
```
pd.read_fwf()
```
##### PARQUET FIEL
```
pd.read_parquet(): Loads data from a Parquet file.

df = pd.read_parquet('file.parquet')
```
##### PICKLE FILE
```
pd.read_pickle(): Loads data from a Pickle file (binary format for serializing Python objects).

df = pd.read_pickle('file.pkl')
```
