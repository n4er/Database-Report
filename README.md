# Database Course Documentation

## Done by Nasser Al Musalhi

## Flat File Systems vs. Relational Databases

| **Aspect**         | **Flat File Systems**                                      | **Relational Databases**                                  |
|--------------------|------------------------------------------------------------|------------------------------------------------------------|
| **Structure**      | Unstructured files such as TXT or CSV without enforced format | Organized in tables with predefined schema (rows & columns) |
| **Data Redundancy**| High; same data often repeated across multiple files       | Reduced through normalization and relational design         |
| **Relationships**  | No support for data linking across files                   | Enforces relationships via primary and foreign keys         |
| **Example Usage**  | Simple data logging, temporary configuration storage       | Inventory systems, HR databases, student records            |
| **Drawbacks**      | Error-prone, lacks scalability and consistency             | Requires DBMS setup, more complex to manage initially       |


## Advantages of Database Management Systems (DBMS) Mind Map

<img width="1921" height="698" alt="mind map" src="https://github.com/user-attachments/assets/ffb869d7-d6fe-42e0-b8b7-bf5e2440872a" />

DBMSs provide essential benefits:  
- **Security**: Access control, encryption, and user verification.  
- **Integrity**: Rules enforce consistency using keys and constraints.  
- **Recovery**: Built-in backup features mitigate data loss.  
- **Concurrency**: Supports multi-user access via isolation and logs.  
- **Redundancy Reduction**: Normalized tables ensure efficient, accurate data handling.

These features allow centralized control, secure collaboration, and robust operations across applications.

## Roles in a Database System

Key roles include:  
- **System Analyst**: Gathers business requirements and defines specifications.  
- **Database Designer**: Builds data models with entities, relationships, and constraints.  
- **Database Developer**: Implements the model using SQL scripts and procedures.  
- **Database Administrator (DBA)**: Manages performance, security, and backups.  
- **BI Developer**: Transforms raw data into insights via tools like Power BI and Tableau.

Each role contributes to the lifecycle and efficiency of the database system.

## Types of Databases

### Relational Databases  
Use structured tables, enforce ACID properties, and suit high-integrity applications like finance and ERP. Examples: MySQL, PostgreSQL, Oracle.

### NoSQL Databases  
Handle unstructured data with flexible models: key-value, document, columnar, and graph. Best for big data and real-time analytics. Examples: MongoDB, Cassandra, Redis.

### Architectures  
- **Centralized**: Single-node control, easy to manage, but less secure.  
- **Distributed**: Data spread across nodes, improving performance.  
- **Cloud-Based**: Scalable, accessible, managed by providers like AWS RDS, Azure SQL, Google Cloud Spanner.

## Cloud Storage and Databases
Cloud storage supports both relational and NoSQL databases, allowing flexible, on-demand infrastructure with global accessibility. Providers handle replication, patching, and disaster recovery. Benefits include reduced hardware costs and scalability. Challenges include compliance, latency, vendor lock-in, and pricing risks. Despite these, cloud adoption continues to rise due to its agility and efficiency.

## Conclusion

This report covers key database concepts: storage types, DBMS benefits, professional roles, database models, and cloud integration. It provides a foundational understanding to guide academic projects and real-world data system implementations.

## References
Database System Concepts (Silberschatz, Korth, Sudarshan) 
https://highered.mheducation.com/sites/0078022150

Fundamentals of Database Systems (Elmasri & Navathe)
https://www.pearson.com/en-us/subject-catalog/p/fundamentals-of-database-systems/P200000006017

Database Systems: A Practical Approach (Connolly & Begg)
https://www.pearson.com/en-us/subject-catalog/p/database-systems-a-practical-approach-to-design-implementation-and-management/P200000006701

MongoDB – NoSQL Explained
https://www.mongodb.com/nosql-explained

Amazon RDS – Cloud Databases Overview
https://aws.amazon.com/rds/
