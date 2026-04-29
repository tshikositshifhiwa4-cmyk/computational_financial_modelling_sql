<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=220&section=header&text=Computational%20Financial%20Modeling%20(SQL)&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=BrightLearn%20Practical%20Assessment%20&descAlignY=58&descSize=16" alt="header"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SQL-Engineering-203A43?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/Platform-SSMS-2C5364?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-Computational%20Finance-0F2027?style=for-the-badge" />
</p>

---

# Overview

This project demonstrates how **financial mathematics can be translated into scalable SQL logic** using **Microsoft SQL Server Management Studio (SSMS)**.

It applies computational thinking to financial engineering by converting mathematical formulas into structured database queries with precision, consistency, and automation.

---

# Project Objective

The purpose of this assessment is to design SQL solutions for financial models while maintaining:

* Mathematical accuracy
* Precision-controlled outputs
* Formula abstraction
* Data consistency
* Financial reporting integrity

---

# Financial Models Implemented

| Task                          | Mathematical Formula         |
| ----------------------------- | ---------------------------- |
| Simple Interest               | `I = P × r × t`              |
| Compound Interest             | `A = P(1 + r)^n`             |
| Hire Purchase                 | `Monthly = [P(1 + rt)] / 36` |
| Inflation Projection          | `A = P(1 + i)^n`             |
| Reducing Balance Depreciation | `A = P(1 - i)^n`             |
| Quarterly Compound            | `A = P(1 + r/4)^(4n)`        |
| Monthly Loan Accrual          | `I = [P(1 + r/12)^12] - P`   |
| Capital Doubling Time         | `t = 1/r`                    |
| Effective Annual Rate         | `EAR = (1 + r/m)^m - 1`      |
| Semi-Annual Growth            | `A = P(1 + r/2)^(2n)`        |

---

# Database Architecture

## Database

```sql
FinancialEngineeringDB
```

## Table

```sql
FinancialTasks
```

| Column       | Description                                  |
| ------------ | -------------------------------------------- |
| `TaskID`     | Unique model identifier                      |
| `ModelName`  | Financial model classification               |
| `Principal`  | Base monetary value                          |
| `AnnualRate` | Interest / Inflation / Depreciation variable |
| `TermYears`  | Time duration                                |
| `Frequency`  | Compounding intervals                        |

---

# Financial Formula Symbol Guide

| Symbol | Meaning                                      | SQL Column        |
| ------ | -------------------------------------------- | ----------------- |
| `P`    | Payments / Original sum of money  | `Principal`       |
| `I`    | Interest                                     |  |
| `r`    | Interest rate                                | `AnnualRate`      |
| `t`    | Time                                         | `TermYears`       |
| `A`    | Annual total amount                          |      |
| `n`    | Number of years                              | `TermYears`       |
| `m`    | Number of conversions per year               | `Frequency`       |
| `i`    | Inflation rate                               | `AnnualRate`      |
| `^`    | Exponent (power of)                          |          |
| `*`    | Multiplication                               |               |
| `/`    | Division                                     |                |
| `+`    | Addition                                     |               |
| `-`    | Subtraction                                  |                |


---

# Repository Structure

```bash
computational-financial-modeling-sql/
│
├── FinancialEngineeringDB.sql
├── Assessment_Solutions.sql
├── Computational_Financial_Modeling.pdf
└── README.md
```

---

# Technical Competencies Demonstrated

## SQL Engineering

* Financial formula implementation
* Mathematical abstraction into SQL
* Dynamic query structuring

## Financial Modeling

* Interest systems
* Inflation forecasting
* Asset depreciation
* Compounding frameworks
* Loan calculations

---

# Strategic Value

This project highlights SQL as more than a querying language.

It demonstrates SQL’s capability as a structured computational system for:

* Financial engineering
* Algorithmic calculations
* Automated business logic
* Precision analytics

---

# Technology Stack

```yaml
Language: SQL
Platform: Microsoft SQL Server Management Studio
Database: SQL Server
Domain: Computational Financial Modeling
Precision Standard: DECIMAL(19,4)
```

---

# Author

### Tshifhiwa Tshikosi

**Data Analytics | Data Engineering | SQL | Financial Modeling**

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer" />
</p>
