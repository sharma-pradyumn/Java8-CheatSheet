# Important Topics in the Database Chapter (Core Java)

## 1. JDBC Overview
- What is JDBC?
- JDBC architecture (DriverManager, Connection, Statement, ResultSet)
- Types of JDBC drivers

## 2. Connecting to a Database
- Loading a JDBC driver
- Establishing a connection (`DriverManager.getConnection()`)
- Handling database URLs

## 3. Executing SQL Statements
- Using `Statement`, `PreparedStatement`, `CallableStatement`
- Difference between **Statement vs. PreparedStatement vs. CallableStatement**
- SQL Injection and how `PreparedStatement` prevents it

## 4. Retrieving Data with `ResultSet`
- Iterating over rows (`ResultSet.next()`)
- Retrieving column values (`getInt()`, `getString()`, etc.)
- Handling NULL values

## 5. Transaction Management
- Auto-commit mode (`setAutoCommit(false)`)
- `commit()` and `rollback()`
- Savepoints (`setSavepoint()`)

## 6. Batch Processing
- Using `addBatch()` and `executeBatch()` for performance

## 7. Metadata Access
- Getting database metadata (`DatabaseMetaData`)
- Getting result set metadata (`ResultSetMetaData`)

## 8. Handling Exceptions
- Try-with-resources (`try (Connection conn = ...)`)
- Handling `SQLException` and `SQLWarning`

## 9. Connection Pooling
- Why pooling is needed
- Using **Apache DBCP**, **HikariCP**, etc.

## 10. RowSet & ORM Overview
- What is `RowSet` and how it differs from `ResultSet`
- Introduction to ORM (Hibernate, JPA)
