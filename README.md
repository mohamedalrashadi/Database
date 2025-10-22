# 🗄️ Database Learning Repository

<div align="center">

**Master Databases Through Structured Learning & Practice**

![Database](https://img.shields.io/badge/Database-4479A1?style=for-the-badge&logo=database&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![NoSQL](https://img.shields.io/badge/NoSQL-4DB33D?style=for-the-badge&logo=mongodb&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active%20Learning-success?style=for-the-badge)

*From beginner to database architect - one level at a time*

</div>

---

## 📖 About This Repository

This repository documents my complete database learning journey, organized into 10 progressive levels. Each level builds upon the previous one, covering SQL, NoSQL, database design, optimization, and real-world applications.

---

## 🗺️ Repository Structure

```
Database/
├── 📚 SQL-Fundamentals/          # Core SQL concepts
├── 🎨 Database-Design/           # Schema design & modeling
├── 🔧 Query-Optimization/        # Performance tuning
├── 🗃️ NoSQL/                     # MongoDB, Redis, etc.
├── 🚀 Projects/                  # Real applications
├── 🔐 Security/                  # DB security practices
└── 📊 Administration/            # DBA tasks & tools
```

---

## 🎯 10-Level Database Mastery Roadmap

### **LEVEL 1: Database Basics** 🌱
*Duration: 1 week | Status: ⬜ Not Started*

**Topics to Master:**
- ✅ What is a Database?
- ✅ DBMS vs File System
- ✅ Types of Databases (Relational, NoSQL)
- ✅ Database Terminology (Table, Row, Column, Key)
- ✅ Installing MySQL/PostgreSQL
- ✅ Database Clients (MySQL Workbench, pgAdmin, DBeaver)
- ✅ Basic SQL syntax structure

**Practice:**
- Install and configure DBMS
- Create your first database
- Explore sample databases (sakila, northwind)
- Write 10 basic SELECT queries

**Folder:** `SQL-Fundamentals/Basics/`

---

### **LEVEL 2: SQL Fundamentals** 📊
*Duration: 2 weeks | Status: ⬜ Not Started*

**Topics to Master:**
- ✅ SELECT queries (WHERE, ORDER BY, LIMIT)
- ✅ Filtering data (AND, OR, NOT, IN, BETWEEN)
- ✅ Pattern matching (LIKE, wildcards)
- ✅ Aggregate functions (COUNT, SUM, AVG, MIN, MAX)
- ✅ GROUP BY & HAVING clauses
- ✅ DISTINCT & NULL handling
- ✅ Basic sorting and limiting results

**Practice:**
- 50+ SELECT query exercises
- Data filtering challenges
- Aggregation problems
- Report generation queries

**Folder:** `SQL-Fundamentals/Queries/`

**Resources:**
- SQLZoo exercises
- HackerRank SQL track
- LeetCode Database problems

---

### **LEVEL 3: Data Manipulation (DML)** 🎨
*Duration: 1-2 weeks | Status: ⬜ Not Started*

**Topics to Master:**
- ✅ INSERT statements (single & bulk)
- ✅ UPDATE operations
- ✅ DELETE operations
- ✅ TRUNCATE vs DELETE
- ✅ INSERT INTO SELECT
- ✅ UPDATE with JOIN
- ✅ Transaction basics (COMMIT, ROLLBACK)
- ✅ ACID properties

**Practice:**
- Data insertion exercises
- Update scenarios
- Safe deletion practices
- Build a simple CRUD system
- Transaction management exercises

**Folder:** `SQL-Fundamentals/DML/`

---

### **LEVEL 4: Database Design & Normalization** 🏗️
*Duration: 2-3 weeks | Status: ⬜ Not Started*

**Topics to Master:**
- ✅ Entity-Relationship Diagrams (ERD)
- ✅ Primary Keys & Foreign Keys
- ✅ Relationships (One-to-One, One-to-Many, Many-to-Many)
- ✅ Normalization (1NF, 2NF, 3NF, BCNF)
- ✅ Denormalization strategies
- ✅ Data Types & Constraints
- ✅ CREATE TABLE statements
- ✅ ALTER TABLE operations
- ✅ DROP & TRUNCATE

**Practice:**
- Design 10+ database schemas
- Normalize sample databases
- Create ERD diagrams
- Build schema for real-world scenarios
  - E-commerce system
  - Social media platform
  - School management system

**Folder:** `Database-Design/Schema-Design/`

**Tools:**
- draw.io for ERDs
- MySQL Workbench Designer
- dbdiagram.io

---

### **LEVEL 5: Advanced SQL Queries** 🧠
*Duration: 3 weeks | Status: ⬜ Not Started*

**Topics to Master:**
- ✅ JOIN operations (INNER, LEFT, RIGHT, FULL, CROSS)
- ✅ Self Joins
- ✅ Subqueries (single-row, multi-row, correlated)
- ✅ EXISTS & NOT EXISTS
- ✅ UNION, INTERSECT, EXCEPT
- ✅ Common Table Expressions (CTE)
- ✅ Window Functions (ROW_NUMBER, RANK, DENSE_RANK)
- ✅ CASE statements
- ✅ String functions
- ✅ Date/Time functions

**Practice:**
- 100+ complex query problems
- LeetCode Medium/Hard database problems
- HackerRank advanced SQL
- Multi-table query challenges
- Report generation exercises

**Folder:** `SQL-Fundamentals/Advanced-Queries/`

---

### **LEVEL 6: Indexes & Query Optimization** ⚡
*Duration: 2-3 weeks | Status: ⬜ Not Started*

**Topics to Master:**
- ✅ How indexes work (B-Tree, Hash)
- ✅ Creating indexes (CREATE INDEX)
- ✅ Unique indexes vs non-unique
- ✅ Composite indexes
- ✅ Index selection strategies
- ✅ EXPLAIN & EXPLAIN ANALYZE
- ✅ Query execution plans
- ✅ Slow query identification
- ✅ Query optimization techniques
- ✅ Statistics & Cardinality
- ✅ Covering indexes

**Practice:**
- Analyze slow queries
- Create optimal indexes
- Compare query performance
- Optimize 20+ queries
- Performance benchmarking exercises

**Folder:** `Query-Optimization/`

---

### **LEVEL 7: Stored Procedures, Functions & Triggers** 🔧
*Duration: 2-3 weeks | Status: ⬜ Not Started*

**Topics to Master:**
- ✅ Stored Procedures (CREATE PROCEDURE)
- ✅ User-Defined Functions (UDF)
- ✅ Parameters (IN, OUT, INOUT)
- ✅ Control flow (IF, CASE, LOOP, WHILE)
- ✅ Cursors
- ✅ Triggers (BEFORE/AFTER INSERT/UPDATE/DELETE)
- ✅ Views (Simple & Complex)
- ✅ Materialized Views
- ✅ Error handling (TRY-CATCH)
- ✅ Dynamic SQL

**Practice:**
- Build 15+ stored procedures
- Create reusable functions
- Implement business logic in database
- Build audit systems with triggers
- Create complex views for reporting

**Folder:** `SQL-Fundamentals/Procedures-Functions/`

---

### **LEVEL 8: NoSQL Databases** 🗃️
*Duration: 3-4 weeks | Status: ⬜ Not Started*

**Topics to Master:**

**MongoDB (Document DB):**
- ✅ Installation & Setup
- ✅ CRUD operations
- ✅ Query operators
- ✅ Aggregation framework
- ✅ Indexes in MongoDB
- ✅ Schema design patterns
- ✅ Relationships & Embedding

**Redis (Key-Value Store):**
- ✅ Data types (Strings, Lists, Sets, Hashes)
- ✅ Pub/Sub messaging
- ✅ Caching strategies
- ✅ Expiration & TTL

**Other NoSQL Types:**
- ✅ Cassandra (Column-family)
- ✅ Neo4j (Graph database)
- ✅ DynamoDB basics

**CAP Theorem & BASE properties**

**Practice:**
- Build MongoDB-based applications
- Implement Redis caching
- Compare SQL vs NoSQL for use cases
- Design schemas for unstructured data
- Migration exercises (SQL to NoSQL)

**Folder:** `NoSQL/`

---

### **LEVEL 9: Database Administration & Security** 🔐
*Duration: 3 weeks | Status: ⬜ Not Started*

**Topics to Master:**
- ✅ User management (CREATE USER, GRANT, REVOKE)
- ✅ Roles & Permissions
- ✅ Backup strategies (Full, Incremental, Differential)
- ✅ Restore operations
- ✅ Replication (Master-Slave, Master-Master)
- ✅ Sharding & Partitioning
- ✅ Connection pooling
- ✅ Monitoring & Logging
- ✅ Performance tuning
- ✅ SQL Injection prevention
- ✅ Database encryption
- ✅ Disaster recovery planning

**Practice:**
- Set up database replication
- Implement backup automation
- Configure user permissions
- Security audit exercises
- Performance monitoring setup

**Folder:** `Administration/` & `Security/`

**Tools:**
- pgBackRest, mysqldump
- Percona Monitoring Tools
- Grafana + Prometheus

---

### **LEVEL 10: Real-World Projects & Advanced Topics** 🚀
*Duration: Ongoing | Status: ⬜ Not Started*

**Advanced Topics:**
- ✅ Database Design Patterns
- ✅ Microservices & Databases
- ✅ Database per Service pattern
- ✅ Event Sourcing & CQRS
- ✅ Time-series databases (InfluxDB, TimescaleDB)
- ✅ Data warehousing concepts
- ✅ ETL pipelines
- ✅ Big Data integration (Hadoop, Spark)
- ✅ Cloud databases (AWS RDS, Azure SQL, Google Cloud SQL)
- ✅ Database migration strategies

**Projects to Build:**

1. **E-Commerce Database System**
   - Complete schema design
   - Product catalog, orders, payments
   - Inventory management
   - Analytics queries

2. **Social Media Platform Database**
   - User profiles & relationships
   - Posts, comments, likes
   - Feed generation optimization
   - Notification system

3. **Hospital Management System**
   - Patient records
   - Appointments & scheduling
   - Doctor-patient relationships
   - Medical history tracking

4. **Banking System Database**
   - Account management
   - Transaction processing
   - Audit trails
   - Fraud detection queries

5. **Real-Time Analytics Dashboard**
   - Time-series data storage
   - Aggregation pipelines
   - Data visualization integration
   - Performance optimization

6. **Multi-Tenant SaaS Database**
   - Tenant isolation strategies
   - Shared schema vs separate schema
   - Cross-tenant analytics

7. **Content Management System (CMS)**
   - Dynamic content storage
   - Version control for content
   - Full-text search implementation
   - Media management

8. **Logistics & Supply Chain DB**
   - Route optimization queries
   - Inventory tracking
   - Order fulfillment
   - Geographic queries

**Folder:** `Projects/`

---

## 📊 Progress Tracker

| Level | Topic | Status | Completion | Exercises Completed |
|-------|-------|--------|------------|---------------------|
| 1 | Database Basics | ⬜ Not Started | 0% | 0/10 |
| 2 | SQL Fundamentals | ⬜ Not Started | 0% | 0/50 |
| 3 | Data Manipulation | ⬜ Not Started | 0% | 0/30 |
| 4 | Database Design | ⬜ Not Started | 0% | 0/10 schemas |
| 5 | Advanced SQL | ⬜ Not Started | 0% | 0/100 |
| 6 | Query Optimization | ⬜ Not Started | 0% | 0/20 |
| 7 | Procedures & Triggers | ⬜ Not Started | 0% | 0/15 |
| 8 | NoSQL Databases | ⬜ Not Started | 0% | 0/25 |
| 9 | Administration | ⬜ Not Started | 0% | 0/20 tasks |
| 10 | Real Projects | ⬜ Not Started | 0% | 0/8 projects |

**Overall Progress:** 0% Complete

---

## 🎯 Learning Strategy

### **Phase 1: Foundation (Levels 1-3)**
Master SQL basics and CRUD operations. Practice daily queries.

### **Phase 2: Design & Advanced Queries (Levels 4-5)**
Learn proper database design and complex query writing.

### **Phase 3: Optimization & Automation (Levels 6-7)**
Focus on performance and database programming.

### **Phase 4: Diversification (Level 8)**
Expand to NoSQL and understand when to use each type.

### **Phase 5: Mastery (Levels 9-10)**
Database administration and building production systems.

---

## 📚 Resources

### **Books:**
- "SQL in 10 Minutes" - Ben Forta
- "Database Design for Mere Mortals" - Michael J. Hernandez
- "High Performance MySQL" - Baron Schwartz
- "MongoDB: The Definitive Guide" - Shannon Bradshaw
- "Designing Data-Intensive Applications" - Martin Kleppmann

### **Online Courses:**
- [Stanford Database Course (Free)](https://online.stanford.edu/courses/soe-ydatabases-databases)
- [MongoDB University (Free)](https://university.mongodb.com/)
- [PostgreSQL Tutorial](https://www.postgresqltutorial.com/)
- [Mode Analytics SQL Tutorial](https://mode.com/sql-tutorial/)

### **Practice Platforms:**
- [LeetCode Database](https://leetcode.com/problemset/database/)
- [HackerRank SQL](https://www.hackerrank.com/domains/sql)
- [SQLZoo](https://sqlzoo.net/)
- [Stratascratch](https://www.stratascratch.com/)
- [DataLemur](https://datalemur.com/)

### **Documentation:**
- [MySQL Documentation](https://dev.mysql.com/doc/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [MongoDB Manual](https://docs.mongodb.com/manual/)
- [Redis Documentation](https://redis.io/documentation)

### **Tools:**
- **SQL Clients:** DBeaver, MySQL Workbench, pgAdmin, DataGrip
- **Design Tools:** dbdiagram.io, draw.io, Lucidchart
- **Cloud Platforms:** AWS RDS, Azure SQL, Google Cloud SQL

---

## ✅ Completion Criteria

Each level is considered complete when:
- ✅ All topics are studied and understood
- ✅ Practice exercises are completed
- ✅ SQL scripts are documented and saved
- ✅ Mini-project or case study is completed
- ✅ Personal notes with examples are written
- ✅ Performance benchmarks are recorded (where applicable)

---

## 💡 Best Practices

### **General:**
- Always use meaningful table and column names
- Document your schema with comments
- Use version control for database scripts
- Write reusable and modular queries
- Test on sample data before production

### **Performance:**
- Index columns used in WHERE, JOIN, ORDER BY
- Avoid SELECT *; specify needed columns
- Use EXPLAIN to analyze queries
- Batch operations when possible
- Monitor slow query logs

### **Security:**
- Never store passwords in plain text
- Use parameterized queries to prevent SQL injection
- Implement least privilege principle
- Regular backups are mandatory
- Encrypt sensitive data

---

## 🤝 Contributing & Feedback

If you're following this roadmap or have suggestions:
- 💡 Share your database design experiences
- 🐛 Report unclear sections or missing topics
- ✨ Suggest additional projects or exercises
- 🤝 Collaborate on complex database projects

---

## 📝 Daily Practice Routine

**Beginner (Levels 1-3):**
- 30 minutes: Read/Watch tutorials
- 30 minutes: Write SQL queries
- Daily goal: 5-10 queries

**Intermediate (Levels 4-7):**
- 20 minutes: Study concepts
- 40 minutes: Complex query practice
- Daily goal: Solve 3-5 problems

**Advanced (Levels 8-10):**
- 15 minutes: Read documentation
- 45 minutes: Work on projects
- Daily goal: Implement 1 feature

---

## 🏆 Milestones

- [ ] Write first SQL query
- [ ] Design first normalized database
- [ ] Solve 50 SQL problems
- [ ] Optimize a slow query 10x
- [ ] Build complete e-commerce schema
- [ ] Master MongoDB CRUD operations
- [ ] Set up database replication
- [ ] Complete 100 LeetCode database problems
- [ ] Build and deploy production database
- [ ] Contribute to database open source project

---

## 🎓 Certification Path (Optional)

- **Oracle Certified Associate (OCA)**
- **Microsoft Certified: Azure Database Administrator**
- **MongoDB Certified Developer**
- **AWS Certified Database Specialty**
- **PostgreSQL Certified Professional**

---

<div align="center">

**🚀 "Data is the new oil, and databases are the refineries."**

*Start Date:* `___/___/___`  
*Target Completion:* `___/___/___`

---

**Last Updated:** October 2025

*Happy Querying! 🗄️*

</div>