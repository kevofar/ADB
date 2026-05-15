# Fitness Center Management System (FCMS) – Advanced Database Features

This repository contains the complete SQL Server 2022 implementation of the Fitness Center Management System, extended with advanced database features as part of the Advanced Database Systems course (InSy3042).

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `01_create_tables.sql` | Creates the database `FCMS_AdvancedDB` and all 12 tables with primary keys, foreign keys, and check constraints. |
| `02_insert_data.sql` | Inserts sample data (members, trainers, classes, payments, etc.). |
| `03_transactions.sql` | Stored procedures `EnrollMember` and `ProcessPayment` using `BEGIN TRAN`, `COMMIT`, `ROLLBACK` (ACID). |
| `04_concurrency.sql` | Demonstrates concurrency control by preventing overbooking (capacity check). |
| `05_query_optimization.sql` | Slow query, indexes, execution plan comparison (Table Scan → Index Seek). |
| `06_security.sql` | Logins, users, roles (`ManagerRole`, `TrainerRole`, `MemberRole`), column‑level `DENY` on `Salary`. |
| `07_backup_recovery.sql` | Full, differential, and transaction log backups with restore sequence. |

## 🚀 How to Run

1. Open **SQL Server Management Studio (SSMS)**.
2. Run the scripts **in order** from `01_create_tables.sql` to `07_backup_recovery.sql`.
3. All advanced features will be installed and tested automatically.

## 🛠️ Requirements

- SQL Server 2022 (or later)
- SQL Server Management Studio (SSMS)

## 📄 Documentation

Full project report (proposal, final report, presentation slides) available separately.

## 👥 Group 6 – Hawassa University IoT Campus

- Ermiyas Sisay
- Estubdink Getachew
- Fanuel Berhane
- Fikeryohannes Wase
- Melat Demtse
- Mitiku Alemayehu
- Moges Mengistu
- Robin Mulugeta

## 📅 Submission Date

May 12, 2026

## 🔗 References

- Elmasri, R., & Navathe, S. B. (2016). *Fundamentals of Database Systems* (7th ed.). Pearson.
- Microsoft SQL Server Documentation (2024). *Backup and Restore*.
- Course guidelines by Instructor Daniel Tesfy.
