<div align="center">

# Club Portal
# 🎓

### A SQL Server database for student scientific clubs

Yearly scripts for a university club desk: students, membership, elections, news, and publications. There is no website in this repository.

<br>

# 👨‍💻 **Sadra Hatami**

### *Developer • Software Engineer • Creator*

<br>

[![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](https://www.microsoft.com/sql-server)
[![T-SQL](https://img.shields.io/badge/T--SQL-Scripts-003B57?style=for-the-badge)](https://learn.microsoft.com/sql/t-sql/language-reference)
[![Database](https://img.shields.io/badge/Database-Election-1ABC9C?style=for-the-badge)](#-what-the-scripts-build)
[![Clubs](https://img.shields.io/badge/Domain-Student%20Clubs-8E44AD?style=for-the-badge)](#-about)
[![Elections](https://img.shields.io/badge/Feature-Elections-C0392B?style=for-the-badge)](#-what-the-scripts-build)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/license/mit)
[![Open Source](https://img.shields.io/badge/Open_Source-Project-black?style=for-the-badge&logo=github)](https://opensource.org/)

<br>

[🌐 GitHub Profile](https://github.com/sadra-hatami)
•
[📧 Email](mailto:sadra.hatami.1732@gmail.com)

</div>

---

# 📑 Table of Contents

- [About](#-about)
- [Why This Repository?](#-why-this-repository)
- [What the Scripts Build](#-what-the-scripts-build)
- [Files](#-files)
- [How to Use](#-how-to-use)
- [Notes](#-notes)
- [FAQ](#-faq)
- [Contact](#-contact)
- [License](#-license)
- [Support](#-support)

---

# 📖 About

**Club Portal** is a SQL Server schema for student scientific associations.

The scripts create and rebuild a database named `Election`. They cover students, club membership, candidates, votes, news, links, and publications. Views and functions summarize members and club state. The yearly files are snapshots of that same desk.

> **Tagline:** *A SQL Server database for student scientific-club records, elections, and yearly scripts.*

This repository holds scripts only. It is not a running portal and it is not a place for real student records.

---

# 🚀 Why This Repository?

A club desk needs more than one table. Membership, voting, and news have to stay linked.

These scripts keep that model in one place:

- A student and a club profile
- An election path with candidates and votes
- News and publications tied to a club
- Yearly SQL files so the schema can be rebuilt

The PHP school desk in [Student Portal](https://github.com/sadra-hatami/Student-Portal) is a separate project.

---

# 🗃️ What the Scripts Build

Objects named in the scripts include:

| Object | Role |
|---|---|
| `student` | Student records |
| `profile` | Student link to a club |
| `vote` | Votes, tied to a student and a candidate |
| `news` | Club news |
| `publication` | Club publications |
| `link` | Related links |
| `club_members` | Membership view |
| `ClubState` | Club-state view |

Triggers and check constraints are also dropped and recreated by the full script.

---

# 📁 Files

| File | Role |
|---|---|
| `Script(v2088_r2).sql` | Full rebuild script |
| `2005.sql` | Year snapshot |
| `2008.sql` | Year snapshot |
| `2012.sql` | Year snapshot |

Do not add `.bak`, `.mdf`, or `.ldf` files. Those are live SQL Server files and can contain real rows.

---

# ▶️ How to Use

1. Open SQL Server Management Studio.
2. Run `Script(v2088_r2).sql` on a local server.
3. Use a year file only if you need that snapshot.

The script starts with `USE [Election]`. Create that database first, or change the name before running.

---

# 📝 Notes

- These files are T-SQL for SQL Server, not MySQL.
- Do not publish real student names, IDs, or votes.
- The repository name says portal. The content is the database behind one.

---

# ❓ FAQ

### Is there a website here?

No. Only SQL scripts.

### Which file should I run?

Start with `Script(v2088_r2).sql`.

### Can I put the backup in git?

No. Keep `.bak`, `.mdf`, and `.ldf` off the repository.

---

# 📬 Contact

**Developer:**

### Sadra Hatami

📧 [Email](mailto:sadra.hatami.1732@gmail.com)

🌐 [GitHub](https://github.com/sadra-hatami)

---

# 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If these scripts are useful as a study sample, please consider giving the repository a ⭐ on GitHub.

---

<div align="center">

## Designed & Developed with ❤️ for the developer community of Iran and the world by **Sadra Hatami**

</div>
