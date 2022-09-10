# SQL database, ORM, Sequelize

# What's the difference between SQL  and NoSQL?
![](https://social.technet.microsoft.com/wiki/cfs-filesystemfile.ashx/__key/communityserver-wikis-components-files/00-00-00-00-05/6433.SQL-vs-NoSQL.jpg)

# What is Sequlize and how to use it with Node js?

##### Sequelize

Sequelize is a modern TypeScript and Node.js ORM for Postgres, MySQL, MariaDB, SQLite and SQL Server, and more.

Featuring solid transaction support, relations, eager and lazy loading, read replication and more.

### to start use Sequelize 

install use commind line 

npm install --save sequelize

conect Sequelize  to Database we have 3 option

```node.js

const { Sequelize } = require('sequelize');

// Option 1: Passing a connection URI
const sequelize = new Sequelize('sqlite::memory:') // Example for sqlite
const sequelize = new Sequelize('postgres://user:pass@example.com:5432/dbname') // Example for postgres


// Option 2: Passing parameters separately (sqlite)
const sequelize = new Sequelize({
  dialect: 'sqlite',
  storage: 'path/to/database.sqlite'
});


// Option 3: Passing parameters separately (other dialects)
const sequelize = new Sequelize('database', 'username', 'password', {
  host: 'localhost',
  dialect: /* one of 'mysql' | 'mariadb' | 'postgres' | 'mssql' */
});


```


# What is an ORM, how does it work, and how should I use one?


Object-relational-mapping is the idea of being able to write queries like this
```sql
SELECT * FROM users WHERE email = 'test@test.com';
```
as well as much more complicated ones, using the object-oriented paradigm of used programming language.


ORM resolves the object code and relational database mismatch with three approaches: bottom up, top-down and meet in the middle.

Each approach has its share of benefits and drawbacks. When selecting the best software solution, developers must fully understand

the environment and design requirements.


In addition to the data access technique, ORM's benefits also include:

- Simplified development because it automates object-to-table and table-to-object conversion, resulting in lower development and maintenance costs
- Less code compared to embedded SQL and handwritten stored procedures
- Transparent object caching in the application tier, improving system performance
- An optimized solution making an application faster and easier to maintain
- 
ORM’s emergence in multiple application development has created disagreement among experts. Key concerns are that ORM does not perform 

well and that stored procedures might be a better solution. In addition, ORM dependence may result in poorly-designed databases in certain circumstances.


### For more information ([click here](https://github.com/qais-alsgher/reading-notes/blob/main/README.md))





