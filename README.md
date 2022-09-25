# Project: The Role of SQL and NoSQL Databases in Data Engineering

## Understanding the differences and characteristics between SQL and NoSQL Databases:

## SQL e NoSQL

Relational databases (SQL) is a database where we store data with a relationship with each other. Used when you need a more rigid system, when you already know what types of data will you relate.

NoSQL = No Only SQL → emerged as an alternative to SQL and not to try to replace. Need came mainly because of scalability (having to store each more information and unstructured data). NoSQL came to supply what relational databases couldn't. They must be used in a way that complements each other.

## SQL Features

Vertical or Horizontal Scalability.

More rigid structure, previously molded, modeled, definition of primary and secondary keys.

Greater consistency, organization.

Performance: Dependent on disk system for performance.

Transactions: Atomicity, consistency, isolation, durability (ACID).

## Features of NoSQL

Horizontal Scalability.

Partitioning (sharding) between nodes

Almost complete absence of schema rules, but there are good practices that must be followed to that it becomes performative.

Less assurance of consistency.

Performance: Depends on cluster size and network latency.

Transactions: Basically available, soft-state, eventually consistent.

Advantages: flexibility, scalability, high performance.

In the case of Mongo, it is recommended to use it for large volume of data, but not recommended in cases of need for Relationships/JOIN, where ACID properties and transactions are and in payment systems, as several payment entities do not approve in systems that customer financial data is not in a relational database.

## Data Engineering
The Data Engineer prepares the information that will be consumed, so he needs to have the technical knowledge to collect, prepare, store and make this information available to that the data scientist uses. The Data Engineer is closer to the manipulation data and has the technical knowledge of the tools. The Engineer will generate these information for data scientist consumption or other information consumption options, therefore it is necessary your knowledge in the different types of Database.
