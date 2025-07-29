# MySQL User Privileges & Data Encryption – SQL Security Simulation

![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Built with SQL](https://img.shields.io/badge/Built%20with-SQL-blue)
![Database: MySQL](https://img.shields.io/badge/Database-MySQL-lightgrey)
![Security: AES & SHA2](https://img.shields.io/badge/Security-AES__SHA2-red)

This project focuses on managing user accounts in MySQL, applying privilege restrictions, and using encryption methods to store sensitive data. It was developed as part of academic coursework and demonstrates real-world scenarios involving database-level security.

---

## 📁 Files

- `erg_3.txt`, `ERG_3i.txt`, `erg_3 .txt`: SQL scripts that include:
  - `CREATE USER`, `GRANT`, `WITH MAX_...` limits
  - Encrypted `INSERT INTO` statements using `AES_ENCRYPT`
  - Hashed passwords with `SHA2()`
  - `SELECT` statements using `AES_DECRYPT`, aliases_
