# MySQL

**SQL (Structured Query Language)** is used for managing and manipulating relational databases. Data is stored in table format, consisting of rows and columns.

---

## 📚 SQL Language Categories

| Category | Name | Commands |
|---------|------|----------|
| 🔧 DDL  | Data Definition Language | `CREATE`, `ALTER`, `DROP`, `TRUNCATE`, `RENAME` |
| 🔍 DQL  | Data Query Language      | `SELECT` |
| ✏️ DML  | Data Manipulation Language | `INSERT`, `UPDATE`, `DELETE` |
| 🔐 DCL  | Data Control Language    | `GRANT`, `REVOKE` |
| 🔁 TCL  | Transaction Control Language | `COMMIT`, `ROLLBACK`, `SAVEPOINT` |

---

## 🛠️ Basic SQL Commands

### 1. Create a Database
```sql
CREATE DATABASE database_name;```

### 2. Show All Databases
```sql
SHOW DATABASES;

### 3. Use a Database
```sql
USE database_name;

### 4. Create a Table
```sql
CREATE TABLE table_name (
  column1 datatype,
  column2 datatype,
  ...
);

### 5. Show Tables in Current Database
```sql
SHOW TABLES;

### 6. Describe Table Structure
```sql
DESC table_name;
-- or
DESCRIBE table_name;

### 7. Insert a Record
```sql
INSERT INTO table_name VALUES (val1, val2, val3, ...);

### 8. Display All Records
```sql
SELECT * FROM table_name;

### 9. Delete Specific Record(s)
```sql
DELETE FROM table_name WHERE column_name = value;

### 10. Update Record(s)

### 8. Display All Records
```sql
SELECT * FROM table_name;

### 9. Delete Specific Record(s)
```sql
DELETE FROM table_name WHERE column_name = value;

### 10. Update Record(s)
```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE column_name = value;

### 11. Truncate Table (Delete All Records)
```sql
TRUNCATE TABLE table_name;

### 12. Drop Table (Delete Table and Records)
```sql
DROP TABLE table_name;

### 13. Alter Table (Add Column)
```sql
ALTER TABLE table_name
ADD column_name datatype;

### 14. Alias (Rename Columns or Tables Temporarily)
```sql
SELECT column_name AS alias_name
FROM table_name;

-----
