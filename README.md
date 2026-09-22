<div align="center">

# 👔 Garment Employee Management System

### A Microsoft Access-Based Database Solution for Garment Factory HR & Employee Management

[![Microsoft Access](https://img.shields.io/badge/Microsoft%20Access-A4373A?style=for-the-badge&logo=microsoftaccess&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/access)
[![Database](https://img.shields.io/badge/Database-MS%20Access%20(.accdb)-0078D4?style=for-the-badge)](https://support.microsoft.com/en-us/office/basic-tasks-for-a-database-9c2f1e34-7a52-4b1b-9e7a-8c1b1e8e5e0a)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)

**A complete Microsoft Access database application** designed to manage garment factory employees — including personal records, attendance tracking, salary processing, department management, and performance evaluation — all through an intuitive Access interface.

[📥 Download](#-getting-started) · [🐛 Report Bug](https://github.com/SIRATHNAYAKA/Garment-Employee-Management-System/issues) · [✨ Request Feature](https://github.com/SIRATHNAYAKA/Garment-Employee-Management-System/issues)

</div>

---

## 📑 Table of Contents

<details open>
<summary>Click to expand / collapse</summary>

- [📌 Overview](#-overview)
- [🎯 Key Highlights](#-key-highlights)
- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [🏗 Database Architecture](#-database-architecture)
- [📂 Project Structure](#-project-structure)
- [🗄 Database Schema](#-database-schema)
- [🚀 Getting Started](#-getting-started)
- [🎮 Usage](#-usage)
- [🖼 Screenshots](#-screenshots)
- [🔐 Security Notes](#-security-notes)
- [🔮 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)

</details>

---

## 📌 Overview

**Garment Employee Management System** is a comprehensive **Microsoft Access** database application built specifically for the garment industry. It digitizes and streamlines the traditionally manual, paper-based processes of employee record management, attendance tracking, salary calculation, and departmental administration.

The system provides a single, centralized database where HR managers and factory supervisors can:

- **Store and manage** complete employee profiles (personal, contact, and employment details)
- **Track daily attendance** — present, absent, late, half-day, and leave records
- **Process monthly salaries** — with allowances, overtime, and deductions
- **Manage departments and designations** — organize workforce structure
- **Generate reports** — employee lists, attendance summaries, salary sheets, and more

Built entirely in **Microsoft Access**, this solution is lightweight, portable, and requires no additional software installation beyond Microsoft Access or the free Access Runtime.

> 💡 **Why this project?** Most garment factories in developing regions still rely on manual registers for attendance and payroll. This Access-based system provides an affordable, instantly deployable digital solution that requires zero programming knowledge to operate.

---

## 🎯 Key Highlights

| 🏆 | Highlight |
| :-: | :--- |
| 👥 | **Complete employee profiles** — personal, contact, and employment data |
| 📅 | **Daily attendance tracking** — present, absent, late, half-day, leave |
| 💰 | **Automated salary processing** — basic pay + allowances + OT – deductions |
| 🏢 | **Department & designation management** — organized workforce structure |
| 📊 | **Built-in reports** — attendance summaries, salary sheets, employee lists |
| 🔍 | **Search & filter** — quickly find employees by ID, name, or department |
| 📋 | **Data validation** — input masks and validation rules prevent errors |
| 🔒 | **Access security** — password-protected database with user-level permissions |
| 📱 | **Portable** — single `.accdb` file, easily backed up and transferred |

---

## ✨ Features

### 👤 Employee Management

| Feature | Description |
| :--- | :--- |
| ➕ **Add Employee** | Register new employees with ID, name, NIC, contact, and address |
| ✏️ **Edit Records** | Update personal and employment details anytime |
| 🔍 **Search Employee** | Find by Employee ID, name, department, or designation |
| 📋 **Employee List** | View all employees in a sortable, filterable table |
| 🗑️ **Deactivate / Delete** | Remove or mark employees as inactive (resigned/terminated) |
| 📄 **Employee Profile** | Consolidated view of all data for a single employee |

### 📅 Attendance Management

| Feature | Description |
| :--- | :--- |
| ✅ **Daily Attendance** | Mark attendance for each employee: Present, Absent, Late, Half-Day, Leave |
| 📆 **Monthly View** | See attendance history for any employee across a month |
| ⏰ **Late Tracking** | Record late arrivals with time and reason |
| 🏖️ **Leave Management** | Track annual, casual, and medical leave balances |
| 📊 **Attendance Summary** | Per-employee and per-department attendance percentage |
| 🔎 **Filter by Date** | View attendance for any specific date range |

### 💰 Salary & Payroll

| Feature | Description |
| :--- | :--- |
| 🧮 **Salary Calculation** | Auto-calculate based on days worked, OT hours, and allowances |
| ➕ **Allowances** | Add transport, meal, and other fixed allowances |
| ⏱️ **Overtime (OT)** | Record OT hours with configurable rate multiplier |
| ➖ **Deductions** | Apply EPF/ETF, loans, advances, and no-pay deductions |
| 🧾 **Salary Sheet** | Generate monthly salary sheets for all employees |
| 🖨️ **Payslip** | Print individual payslips with full breakdown |

### 🏢 Department & Designation

| Feature | Description |
| :--- | :--- |
| 🏭 **Department Management** | Add/edit departments (Sewing, Cutting, Finishing, QA, etc.) |
| 🎯 **Designation Management** | Define job roles (Operator, Supervisor, Manager, etc.) |
| 🔗 **Assign to Employee** | Link each employee to a department and designation |
| 📊 **Department Reports** | Headcount and salary cost per department |

### 📊 Reports & Analytics

| Report | Description |
| :--- | :--- |
| 📋 **Employee Master List** | Complete list with all details — filterable and printable |
| 📅 **Attendance Report** | Daily/monthly attendance with percentages |
| 💰 **Salary Sheet** | Monthly payroll for all or selected employees |
| 🧾 **Payslip** | Individual employee payslip |
| 🏢 **Department Summary** | Headcount and cost per department |
| ⏰ **Overtime Report** | OT hours and cost by employee/department |
| 🏖️ **Leave Report** | Leave balances and usage history |

---

## 🛠 Tech Stack

<div align="center">

| Category | Technology |
| :--- | :--- |
| **Platform** | Microsoft Access (2016 / 2019 / 2021 / 365) |
| **Database File** | `.accdb` (Access Database) |
| **Interface** | Access Forms (Navigation Forms, Data Forms, Dialog Forms) |
| **Reports** | Access Reports (with grouping, sorting, and calculations) |
| **Queries** | Access Queries (Select, Action, Crosstab, Parameter) |
| **Macros / VBA** | Microsoft Visual Basic for Applications (VBA) |
| **Security** | Database password + User-Level Security (if configured) |
| **Runtime** | Microsoft Access Runtime (free) for deployment |

</div>

> **Note:** No external libraries, APIs, or internet connection required. Everything runs locally within Microsoft Access.

---

## 🏗 Database Architecture

The system follows a **relational database design** normalized to **Third Normal Form (3NF)** to eliminate data redundancy and ensure integrity.
