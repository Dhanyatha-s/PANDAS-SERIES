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
##### GOOGLE BIGQUERY
```
pd.read_gbq(): Loads data from Google BigQuery (requires pandas-gbq package).

df = pd.read_gbq('SELECT * FROM dataset.table', project_id='your_project_id')
```
##### OTHERS 
```
read_stata(): Loads data from a Stata file.
read_sas(): Loads data from a SAS file.
read_spss(): Loads data from an SPSS file.
read_sql_table(): Loads data from a SQLAlchemy-compatible database table.
```
