#Relational Databases
A relational database, also called Relational Database Management System (RDBMS) or SQL database, stores data in tables and rows also referred to as records. Structured Query Language (SQL) is the most common language for reading, creating, updating and deleting data. Relational databases are very reliable. They are compliant with ACID (Atomicity, Consistency, Isolation, Durability), which is a standard set of properties for reliable database transactions. Relational databases work well with structured data.
Examples: Microsoft SQL Server, Oracle Database, MySQL, PostgreSQL and IBM Db2
##Use Case
- eCommerce applications.
- LAMP open source stack
- General purpose OLTP database
Facebook uses MySQl as it's primary database management system for all structured data storage such as the different wall posts, information of various users, their timeline.
##Pros
- Relational databases work with structured data.
- They support ACID transactional consistency and support “joins.”
- They come with built-in data integrity and a large eco-system.
- Relationships in this system have constraints.
- There is limitless indexing.
##Cons
- Relational Databases do not scale out horizontally very well (concurrency and data size), only vertically, (unless you use sharding).
- Data is normalized, meaning lots of joins, which affects speed.
- They have problems working with semi-structured data.

#Non Relational Databases
Non-relational databases are also called NoSQL databases. NoSQL has become an industry standard term, but the name is beginning to lose popularity since it doesn’t fully cover the complexity and range of non-relational data stores that are available. Some of the most known NoSQL or non-relational DBs are Document-oriented database, Graph database, Object-oriented database
##Document-oriented Databases
A document-oriented database is a type of NoSQL database in which data is stored in binary document files. This type of database associates each document with a unique key that takes the form of a string, path or URI. Keys are used to locate and pull individual documents from the database. A document-oriented database may also be referred to as a document store.
- MongoDB is one of the most popular examples of a document-oriented database. It includes features such as full index support, replication and sharding. A core function of MongoDB is its horizontal scalability
###Use Case
- Companies running big data applications.
- Mobile App development.
- Real-Time Analytics.
- Gaming.

##Graph Database
Graph databases are purpose-built to store and navigate relationships. Relationships are first-class citizens in graph databases, and most of the value of graph databases is derived from these relationships. Graph databases use nodes to store data entities, and edges to store relationships between entities. An edge always has a start node, end node, type, and direction, and an edge can describe parent-child relationships, actions, ownership, and the like. There is no limit to the number and kind of relationships a node can have.
- Amazon Neptune is a fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. The core of Amazon Neptune is a purpose-built, high-performance graph database engine optimised for storing billions of relationships and querying the graph with milliseconds latency
###Use Case
- Recommendation engines.
- Fraud detection.

##Object-Oriented Database
An object-oriented database is a database management system in which information is represented in the form of objects as used in object-oriented programming. Object databases are different from relational databases which are table-oriented. Object–relational databases are a hybrid of both approaches.
- Realm is an object and mobile database. It’s a data-storage solution for mobile and web development.
###Use Case
- Mobile development.
- Offline based applications.

##Pros Of Non Relational Databases
- Flexible Scalability.
- Stores Massive Amounts Of Data.
- Database Maintenance.
-  Economical.
##Cons Of Non Relational Databases
- Less Support
- Limited Business Analytics And Intelligence
- Not Mature
