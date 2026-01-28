# Task 3 – API Security Risk Analysis

This repository contains Task 3 submission for the **Future Interns Cyber Security Internship**.

The objective of this task is to analyze a public API, identify potential security risks, and recommend mitigation strategies.

---

## 🌐 API Analyzed
https://jsonplaceholder.typicode.com/users  
(Public demo API used for testing and learning purposes.)

---

## 🛠 Tools Used
- Browser
- Postman (optional)

---

## 🔍 Security Risks Identified

### 1. No Authentication Required
- **Risk Level:** High  
- **Impact:** Anyone can access sensitive user data.
- **Recommendation:** Implement authentication tokens or API keys.

---

### 2. Data Exposure
- User information returned without restrictions.
- **Risk Level:** Medium  
- **Recommendation:** Limit exposed fields and enforce access control.

---

### 3. No Rate Limiting
- Unlimited requests allowed.
- **Risk Level:** Medium  
- **Recommendation:** Apply rate limiting to prevent abuse.

---

## 📚 Key Learnings
- API security fundamentals
- Risk identification
- Secure API design principles

---

## ⚠ Disclaimer
This analysis is for educational purposes using a public demo API.

---

## ✅ Task Status
✔ Completed  
✔ Internship Ready
