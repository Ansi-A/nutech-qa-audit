# 🔍 NUTECH University – Website QA Audit & Defect Report

A comprehensive **manual QA audit** conducted on official NUTECH University websites to identify functional defects, broken links, and potential exposure risks.

This audit resulted in the identification of **40+ critical and medium-impact issues**, all formally documented and reported to the university’s ICT department. The reported issues were acknowledged and subsequently resolved.

---

## 🎯 Project Objective

To evaluate the reliability, accessibility, and functional integrity of publicly accessible university web portals using structured manual testing techniques and professional defect reporting standards.

---

## 🌐 Websites Audited

- https://nutech.edu.pk  
- https://skills.nutech.edu.pk  

---

## 📊 Audit Summary

- **Testing Type:** Manual QA (Black-Box Testing)  
- **Total Issues Identified:** 40+  
- **Error Categories:**
  - 404 (Page Not Found)
  - Server Timeout
  - Bad Host Configuration
  - Internal IP / Localhost Exposure
  - Broken Navigation Links
- **Evidence:** Screenshot provided for every reported issue  
- **Reporting Format:** Structured Excel Bug Log + Formal PDF Audit Report

  ## 📊 Bug Log Preview

The screenshot below demonstrates:

- Structured defect tracking
- Severity classification (Critical / High / Medium)
- Clear reproduction steps
- Suggested fixes
- Issue resolution status (Closed)

<img width="1606" height="543" alt="image" src="https://github.com/user-attachments/assets/42805d36-f6b4-4189-a2d9-757d89a30085" />

<img width="1774" height="550" alt="image" src="https://github.com/user-attachments/assets/7512e8bd-b3e5-41a7-9112-fdb9ac0fa9f1" />




Full detailed log available in `NUTECH_QA_Broken_Links_Report_All_ - NUTECH_QA_Broken_Links_Report_All_60.csv.pdf` or the link :-

https://docs.google.com/spreadsheets/d/1r0q2uzRVwmxJRXWalnWKldRG1vjrlYPoNcKFNa1vr4g/edit?usp=sharing
  

---

## 🧠 Testing Approach

- Manual navigation testing across all accessible pages
- Link integrity validation
- Identification of internal IP and localhost exposures
- Error classification and severity tagging
- Clear documentation of reproducible steps
- Structured bug logging for developer clarity

---

## 🛠 Tools Used

- Web Browser (Chrome / Firefox)
- Microsoft Excel (Bug Tracking & Logging)
- Screenshot Capture Tools
- PDF Report Documentation

---

## 📄 Deliverables

| File | Description |
|------|-------------|
| bug_log.xlsx | Complete bug list with reproduction steps |
| QA_Report_NUTECH.pdf | Formal structured audit report |
| screenshots/ | Screenshot evidence for each reported defect |
| README.md | Project documentation |

---

## 🐞 Bug Report Format 

**Bug ID:** TC-001  
**Affected Page:** https://skills.nutech.edu.pk  
**Broken Link:** /weekend-grid.php  
**Issue Type:** Server Timeout  
**Severity:** Medium  

### Steps to Reproduce:
1. Navigate to the Skills Portal  
2. Click on “Weekend Courses”  
3. Observe page loading failure  

**Expected Result:** Page loads successfully  
**Actual Result:** Timeout error  

**Suggested Fix:** Verify DNS configuration and server availability.

---

## 📬 Official Acknowledgement

The identified issues were formally reported to the NUTECH ICT department.

The ICT Office confirmed that the reported broken links were updated and appreciated the initiative in improving system reliability.

Screenshot of official email confirmation attached in repository.

<img width="1563" height="427" alt="image" src="https://github.com/user-attachments/assets/7e1be0fd-3b21-48cb-af03-41282cb1b7a5" />


---

## 🚀 Impact

This project demonstrates:

- Strong manual testing fundamentals
- Structured defect documentation
- Real-world issue identification
- Clear communication with stakeholders
- Initiative beyond academic requirements
- Practical understanding of web system reliability

---

## 👤 Author

Muhammad Salman  
QA Automation & Manual Testing 

---

## 📄 License

This project is licensed under the MIT License.
