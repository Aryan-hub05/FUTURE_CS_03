# 🔐 Task 3 – API Security Risk Analysis  
**Future Interns – Cyber Security Internship**

## 📌 Objective
The objective of this task is to analyze a public/demo API for common security risks related to authentication, authorization, data exposure, rate limiting, and input validation, and to document the findings in a professional and business-friendly manner.

---

## 🌐 Target API
**API Tested:** Public / Demo API  
(Used strictly for educational and legal testing purposes)

---

## 🛠️ Tools Used
- Postman  
- Browser Developer Tools  
- Public Sample API  

---

## 🔍 API Security Findings

### 1️⃣ Weak / Missing Authentication
- **Risk Level:** Medium  
- **Issue:** API endpoints can be accessed without strong authentication mechanisms.  
- **Impact:** Unauthorized users may access or manipulate API data.  
- **Recommendation:**  
  Implement token-based authentication (JWT / API Keys) and enforce access control on all sensitive endpoints.

---

### 2️⃣ Excessive Data Exposure
- **Risk Level:** Medium  
- **Issue:** API responses return unnecessary or sensitive fields.  
- **Impact:** Attackers can gather internal or user-related information.  
- **Recommendation:**  
  Apply response filtering and return only required data fields.

---

### 3️⃣ Missing Rate Limiting
- **Risk Level:** Medium  
- **Issue:** Unlimited API requests are allowed from a single client.  
- **Impact:** Can lead to brute-force attacks or denial-of-service (DoS).  
- **Recommendation:**  
  Implement rate limiting and request throttling on API endpoints.

---

### 4️⃣ Input Validation Issues
- **Risk Level:** Medium  
- **Issue:** User inputs are not properly validated or sanitized.  
- **Impact:** May allow injection attacks such as SQL Injection or XSS.  
- **Recommendation:**  
  Validate and sanitize all user inputs on the server side.

---

## 📊 Risk Summary

| Vulnerability | Risk Level |
|--------------|-----------|
| Weak Authentication | Medium |
| Data Exposure | Medium |
| Missing Rate Limiting | Medium |
| Input Validation Issues | Medium |

---

## 📸 Evidence
Screenshots of Postman requests and API responses are included in the repository to support the findings.

---

## 📚 Key Learnings
- API security fundamentals  
- Authentication & authorization risks  
- Importance of rate limiting  
- Secure API documentation practices  

---

## ⚠️ Disclaimer
This API security analysis was conducted **only for educational purposes** on a legal testing API.  
No exploitation or harmful activity was performed.

---

## ✅ Task Status
✔ Completed  
✔ GitHub Documented  
✔ Internship Ready
