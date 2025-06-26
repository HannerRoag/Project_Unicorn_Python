
<h1> Unicorn Project - Analizyng INE statistics <h1>

### 1. Data source
 INE - National Institute of statistics of Spain
 
### 2. Objectives
#### 2.1 Main objective
- Using external information, development knowledge using python.
#### 2.2. Specific objetives 
- Development libreries and methods on Python.
- Analyze information provided for INE.
- Visualyze relevant information.

### 3. Tecnologies
![SQL](https://img.shields.io/badge/-Sql-f29111?style=for-the-badge&logo=mysql)
![Jupyter](https://img.shields.io/badge/-Jupyter-white?style=for-the-badge&logo=Jupyter)
![Python](https://img.shields.io/badge/-Python-9370DB?style=for-the-badge&logo=Python)

### 4. Key question
##### Do the trends for the male and female groups follow the same pattern?

### 5. Development of analysis
#### 5.1 Connection INE ![Jupyter](https://img.shields.io/badge/-Jupyter-white?style=for-the-badge&logo=Jupyter)
The connection is established with an external data source, the connection is adjusted to the required of the data source.
- Import libraries as pandas, requests, datetime.
- Function that take a code INE, connection and return a Json with requested data.
- Read the archive with the serie code of INE.
- Take the attributes of each data serie.
- Make the dataframe with data lists.
#### 5.2 Daraframe exploration ![Jupyter](https://img.shields.io/badge/-Jupyter-white?style=for-the-badge&logo=Jupyter)
- Use the methods as .rename(), .max(), .min(), .mean(), .unique(), .split(), .groupby(), .agg(), .transform(), .apply(). <br/>
.info(), .year(), .month(), .to_dataframe(), .dir(), .shift(), .assign(), .columns(), .loc(), .cut(), .sample().
#### 5.3. DDSS Connection ![SQL](https://img.shields.io/badge/-Sql-f29111?style=for-the-badge&logo=mysql) ![Jupyter](https://img.shields.io/badge/-Jupyter-white?style=for-the-badge&logo=Jupyter)
- Import or libraries as mysql-connect-python, pymysql, sqlalchemy.
- Configuration of connection.
- Consult data sources.
- Make connections.
- Close connection.
- Save dataframe as .csv using method .to_csv().
#### 5.4 Visualization in python ![Jupyter](https://img.shields.io/badge/-Jupyter-white?style=for-the-badge&logo=Jupyter)
- Import libraries as os, numpy, pandas, datetime, matplotlib.piplot, seaborn.
- Use methods as .read_csv(), .info(), .to_datatime(), .plot(), .figure(), .show(), .xlabel(), .ylabel(), .title().

  ### 6. Conclusions of analysis
  
