# pythoncasestudy-1

# Python Activity-Based Learning — 10 Solved Case Studies

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Dependencies](https://img.shields.io/badge/Dependencies-None%20(Pure%20Python)-brightgreen)
![Course](https://img.shields.io/badge/Branch-C.S.E-orange)

A collection of **10 practical Python case studies** solved as part of the Activity-Based Learning (ABL) assignment. Each solution is built strictly using foundational Python concepts—variables, data types, operators, conditional statements, loops, strings, pattern generation, lists, nested lists, tuples, tuple unpacking, and formatted output—without external libraries, dictionaries, sets, or custom functions.

---

## Submission Details

| Field | Details |
| :--- | :--- |
| **Submitted By** | Gani Varshith Sai Koduri |
| **Roll Number** | `26000575` |
| **Course / Branch** | C.S.E |
| **Institution** | Dr. R.V.R NRI University |

---

## Case Studies Overview

| Case No. | Q. No. | Case Study Title | Script File | Core Concepts Used |
| :---: | :---: | :--- | :--- | :--- |
| 1 | Q1 | University Scholarship Allocation | | Tuples, nested-loop sorting, tie-breaking logic |
| 2 | Q2 | Progressive Electricity Billing | | Multi-slab conditionals, sequential comparison |
| 3 | Q6 | Railway Fare and Reservation Calculator | | Nested branching, concessions, revenue tracking |
| 4 | Q13 | ATM Transaction Sequence Simulation || State management, validation rules, audit logs |
| 5 | Q27 | Advanced Numeric Pattern Generator |  | Input validation, nested loops, geometric spacing |
| 6 | Q29 | Password Policy Validation Engine || Character scanning, triplet checks, substring checks |
| 7 | Q31 | String-Based Examination Answer Evaluation | | Index-wise comparison, negative marking, statistics |
| 8 | Q35 | Text Compression Using Character Runs | | Run-Length Encoding (RLE), compression analysis |
| 9 | Q43 | Multi-Branch Sales Matrix Comparison |  | 3D nested lists, multi-level aggregation |
| 10 | Q48 | Tuple-Based Employee Shift Conflict Detection |  | Tuple unpacking, pairwise interval overlap checks |

---

## Detailed Case Study Breakdown

### 1. University Scholarship Allocation (`Q1`)
Evaluates applicants across 3 subjects against eligibility thresholds (aggregate ≥ 75%, minimum subject score ≥ 60, attendance ≥ 80%, annual family income ≤ ₹4,00,000). Ranks eligible candidates using deterministic tie-breaking (higher aggregate → higher attendance → lower income) and lists exact rejection reasons for ineligible applicants.

### 2. Progressive Electricity Billing (`Q2`)
Computes monthly bills across four tiered consumption slabs (₹3, ₹5, ₹7, and ₹9/unit) plus a ₹100 fixed charge, applying a 5% conservation rebate for ≤ 100 units and a 10% surcharge for > 300 units. Compares consecutive months to flag bill increases exceeding 25%.

### 3. Railway Fare and Reservation Calculator (`Q6`)
Calculates itemized passenger fares using distance slabs (0–100 km, 101–300 km, > 300 km), travel class multipliers and reservation fees (`SL`, `3A`, `2A`), and age-based concessions (free for < 5 years, 50% off for 5–12 years, 40% off for ≥ 60 years). Handles time-based cancellation penalties and summarizes net revenue.

### 4. ATM Transaction Sequence Simulation (`Q13`)
Processes a sequence of deposits and withdrawals while enforcing banking rules: ₹1,000 minimum balance, ₹10,000 per-transaction limit, ₹20,000 daily withdrawal limit, and ₹100 denomination multiples. Generates a complete transaction audit log and closing balance summary.

### 5. Advanced Numeric Pattern Generator (`Q27`)
Validates user-entered dimensions (`2 ≤ n ≤ 9`) and generates an aligned hollow numeric diamond spanning `2n - 1` rows using nested spacing loops.

### 6. Password Policy Validation Engine (`Q29`)
Inspects multiple passwords for minimum length (≥ 8), uppercase/lowercase letters, digits, special characters, absence of spaces, no 3+ consecutive repeated characters, and case-insensitive prohibited substrings (`password`, `admin`, `1234`, `qwerty`, `welcome`). Reports every failed condition individually.

### 7. String-Based Examination Answer Evaluation (`Q31`)
Evaluates student answer strings against an official key with `+4` for correct answers, `-1` for wrong answers, and `0` for unanswered (`-`) entries. Flags length mismatches as invalid submissions, determines `PASS`/`FAIL` status (40% threshold), and outputs the class average and top scorer.

### 8. Text Compression Using Character Runs (`Q35`)
Implements lossless Run-Length Encoding (RLE) by grouping consecutive identical characters, calculates percentage space saved, and advises whether to use the compressed string or retain the original when encoding is not beneficial.

### 9. Multi-Branch Sales Matrix Comparison (`Q43`)
Models branch, product, and day-wise sales in a 3D nested list (`sales[branch][product][day]`). Aggregates per-branch totals, identifies the best-performing product in each branch, computes overall product totals, and highlights the top-performing branch.

### 10. Tuple-Based Employee Shift Conflict Detection (`Q48`)
Stores employee shifts as immutable tuples `(emp_id, name, day, start_hr, end_hr)` in 24-hour format, validates interval bounds (`0 ≤ start < end ≤ 24`), and runs pairwise comparisons to detect overlapping shifts while allowing adjacent back-to-back shifts.

---

## Repository Structure

```text
Python-Activity-Based-Learning/
├── case_01_scholarship_allocation.py
├── case_02_electricity_billing.py
├── case_03_railway_fare.py
├── case_04_atm_simulation.py
├── case_05_numeric_pattern.py
├── case_06_password_validation.py
├── case_07_exam_evaluation.py
├── case_08_text_compression.py
├── case_09_sales_matrix.py
├── case_10_shift_conflicts.py
├── Python Activity-Based Learning - 10 Solved Case Studies.pdf
└── README.md
