# TODO: lookup different kinds of database
# TODO: lookup the definition of relational database
# TODO: learn basic sql through [w3school's SQL tutorial](https://www.w3schools.com/sql/)
# SQLite: a simple yet very power database
- extremely lightweight
- native support from many applications and platforms
- highly portable as data is stored in a single .db file
- can be browsed like an excel worksheet using [DB Browser for SQLite](https://sqlitebrowser.org/)

# Other commonly used databases:
- PostgreSQL
- MySQL
- MSSQL
- etc.

# How do you connect to a database?
- Databases can be a single file on your computer
- They can also live on other servers and be accessible via a url, port, username, and pswd
- How the connection is actually handled can be abstracted away by packages like SQLAlchemy
- SQLAlchemy allows you to create a connection object using a simple connection string and handle sql queries through it
- The connection object can even directly interact with tools like Pandas to manupulate data

# TODO:
- Install SQLAlchemy in your python env
- Look up SQLAlchemy connection string
- Create a local SQLite database
- Read the sample json file under [data](/data) into python and explore its content
- Think of how you can cleanly separate the content of this file into several tables and save them as pandas dataframes
- Connect to this database using SQLAlchemy
- Look up how to insert dataframes into tables using Pandas and connection objects
- Look up how to read from the tables you just inserted and test read
- Use DB Browser to open us the db file and see if the tables match what you expect
- Look up how PostgreSQL connections are created. Do you see differences/similarities to SQLite?
