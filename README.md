# 🛡️ Bug Report - Production Dispatch System

This repository contains a structured QA bug report for the **Production Dispatch System** application. The report aggregates issues identified across multiple testing cycles to help ensure that the application delivers accurate, efficient, and error-free dispatch operations.

---

## 📋 Project Overview

The **Production Dispatch System** is developed to handle and streamline the dispatching of production materials through various job and box-handling workflows. This bug report highlights critical system limitations, user experience issues, and data integrity bugs found during manual testing sessions.

---

## ✅ Test Summary

| Category              | Count   |
|-----------------------|---------|
| Total Test Cases      | ~120     |
| Test Cases Passed     | ~103     |
| Test Cases Failed     | ~37     |
| Total Bugs Reported   | 37     |
| Critical Bugs         | 25      |
| Minor Bugs            | 12       |
| Test Coverage         | ~90%    |

---

## 📁 File Details

- **File Name**: `production_dispatch_system.csv`
- **Columns Include**:
  - Issue Key
  - Summary
  - Issue Type
  - Status
  - Created & Updated Dates
  - Priority, Assignee
  - Project Name & Type
  - Status Category
  - Other custom fields

---

## 🔍 Sample Bug Entry

| Field               | Example Value                                                           |
|--------------------|--------------------------------------------------------------------------|
| **Bug ID**         | PDSA-22                                                                  |
| **Summary**        | Switching drop down doesn't clear the data                               |
| **Severity**       | Critical                                                                 |
| **Status**         | To Do                                                                    |
| **Steps to Reproduce** | 1. Open job list <br>2. Switch to another dropdown without resetting values |
| **Expected Result**| Fields reset upon selection change                                       |
| **Actual Result**  | Old data persists and causes dispatch mismatches                         |
| **Reported Date**  | Dec 29, 2024                                                             |

---

## 🔧 Modules Tested

- Job & Box Assignment Workflow
- Dispatch Flow Validations
- Re-assigning and Barcode Handling
- Quantity Input Validations
- Dropdown & State Management
- Sync & Save Button Behavior

---

## 🎯 Purpose

This report was created to:

- Provide a comprehensive snapshot of open and resolved bugs
- Help the development team prioritize and reproduce issues quickly
- Document user experience flaws and logic errors in dispatch operations
- Strengthen production integrity and data consistency

---

## 🙋‍♂️ Author

**Name**: Md. Sadman Shahrieal Pieal  
**Role**: QA Engineer  
**Email**: sadmanpieal@gmail.com  
**Date**: April 2025

---

## 🧭 Future Enhancements

- Automate dropdown and field reset validation tests
- Introduce form data integrity testing across module transitions
- Conduct regression testing for fixed bugs
- Integrate test scripts with CI pipeline for nightly QA builds

---

## 📌 Disclaimer

This document is intended for QA and engineering purposes only. All information contained is based on manual verification efforts and will evolve with subsequent testing rounds.
