### Database Connection

Setting up connections to different Databases, and read and write into one.
We will be connecting to the SQLite, PostgresSQL and MS SQL Server.

### Environment Setup

Step 1: Create Environment
```
conda create --name databaseenv python=3.9 -y
```
Step 2: Activate Environment
```
conda activate databaseenv
```
Step 3: Install the required packages and dependencies
```
pip install pandas matplotlib sqlalchemy pymysql pscopg2-binary pyodbc jupyter
```
### Code Structure

|-- credentials
|-- data
|-- data_ingestion
|-- sqlite
|-- postgressql
|-- ms sql server
|-- writing data to database
|-- README.md

### Important links
```
https://trenton3983.github.io/files/projects/2019-03-22_intro_to_databases_in_python/2019-02-12_intro_to_databases_in_python.html#Data-Files-Location
```