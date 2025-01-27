State and Explain the components of a DBMS(Database Management System) 
Database Engine: This is the core component responsible for managing and retrieving data from the database. It handles the physical storage, data manipulation, and querying of the database.

Database Schema: It defines the logical structure of the database. It specifies how data is organized, including tables, fields, relationships, and constraints.

Query Processor: This component interprets and processes SQL queries, converting them into a sequence of operations that can be executed by the database engine.

Database Management Software (DBMS Software): This is the software that provides the interface and tools for managing databases, including user interfaces, data backup, security management, and other administrative functions.

Transaction Management: Ensures that database transactions are processed reliably, maintaining ACID (Atomicity, Consistency, Isolation, Durability) properties.

Data Dictionary: A metadata repository that stores information about the structure and constraints of the database, such as tables, fields, data types, and relationships.

Security and Access Control: Manages user permissions and access levels, ensuring data privacy and integrity.

What is a relational database? Give 4 examples.
A relational database organizes data into tables (relations) consisting of rows (records) and columns (attributes). Relationships between tables are established using keys (e.g., primary and foreign keys).

Examples:

MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database

State and Explain three classifications of SQL?
Data Definition Language (DDL): Used to define the structure of the database, including commands like CREATE, ALTER, and DROP. DDL deals with the creation and modification of database schema.

Data Manipulation Language (DML): Used to manipulate the data within the database. This includes commands like SELECT, INSERT, UPDATE, and DELETE.

Data Control Language (DCL): Used to control access to data in the database. The main commands include GRANT (to give access rights) and REVOKE (to remove access rights).

What is the difference between a Primary Key and a Foreign Key?
Primary Key: A primary key is a field or a combination of fields in a table that uniquely identifies each record. It cannot have duplicate or null values.

Foreign Key: A foreign key is a field in one table that links to the primary key of another table. It is used to maintain referential integrity between the two tables.

What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the relationships between entities in a database. It uses symbols like rectangles (for entities), diamonds (for relationships), 
and ovals (for attributes) to depict how data is related.

What are the advantages of relational databases?

Data Integrity: Ensures accuracy and consistency of data using constraints like primary and foreign keys.
Flexibility: Allows for complex queries and efficient data retrieval.
Normalization: Reduces data redundancy by organizing data into multiple related tables.
ACID Compliance: Ensures reliable transactions with Atomicity, Consistency, Isolation, and Durability.

State four types of data type used to store data in tables?
Integer: Used to store whole numbers (e.g., INT, BIGINT).
Varchar: Used to store variable-length strings of text (e.g., VARCHAR).
Date/Time: Used to store date and time values (e.g., DATE, DATETIME).
Decimal/Float: Used to store numbers with decimal places (e.g., DECIMAL, FLOAT).

What is the purpose of a database management system (DBMS)?
The purpose of a DBMS is to provide an efficient, secure, and organized way to manage data. It enables:

Centralized data storage and access.
Data consistency and integrity.
Simplified data sharing among multiple users.
Secure and controlled access to data.
Improved performance in handling large data sets.

