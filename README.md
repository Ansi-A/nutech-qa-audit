# 🔍 NUTECH University – QA Web Audit

This project is a **complete manual QA audit** of the **NUTECH University** websites.  
The audit identifies and documents **40+ broken or non-functional links**, including internal IP exposures, `404` errors, timeouts, and bad host issues.

📊 **Audit Report (Google Sheet):**  
https://docs.google.com/spreadsheets/d/1r0q2uzRVwmxJRXWalnWKldRG1vjrlYPoNcKFNa1vr4g/edit?usp=sharing

---

## 📌 Project Summary

- 🔧 **Type:** Manual QA Testing (Black-Box)
- 🖥 **Websites Audited:**  
  - https://nutech.edu.pk  
  - https://skills.nutech.edu.pk
- 🐞 **Total Bugs Reported:** 40+
- 💥 **Error Types Identified:**  
  `404`, `Timeout`, `Bad Host`, `Localhost / Internal IP Exposure`
- 🧪 **Testing Tools Used:**  
  Web Browser, Excel, Screenshot Tools
- 🧾 **Reporting Format:**  
  Structured Excel Sheet + PDF Report
- 📸 **Evidence:**  
  Screenshots provided for each reported issue

---

## 📄 Deliverables

| File | Description |
|------|------------|
| `bug_log.xlsx` | Complete bug list with steps to reproduce |
| `QA_Report_NUTECH.pdf` | Final audit report in PDF format |
| `screenshots/` | Screenshots for every reported bug |
| `README.md` | Project overview |
| `LICENSE` | MIT License |

---

## 📊 Bug Sample (TC-001)

| Field | Value |
|------|------|
| **Bug ID** | TC-001 |
| **Page URL** | https://skills.nutech.edu.pk |
| **Broken Link** | https://skills.nutech.edu.pk/weekend-grid.php |
| **Link Purpose** | Weekend Courses |
| **Steps to Reproduce** | Click the link or navigate manually |
| **Expected Result** | Page loads successfully |
| **Actual Result** | TIMEOUT error |
| **Error Type** | TIMEOUT |
| **Severity** | Medium |
| **Suggested Fix** | Check server availability or DNS configuration |

---

## 📁 Screenshots

Each reported issue includes a screenshot stored in the `/screenshots` directory for verification and evidence.

---

## 👤 Author

**Muhammad Salman**  
Manual & Automation QA Tester

---

## 📄 License

This project is licensed under the **MIT License**.
