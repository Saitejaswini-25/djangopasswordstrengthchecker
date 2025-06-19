# 🔐 Django Password Strength Checker

A Cybersecurity-focused web application built using **Python** and **Django** that analyzes password strength and promotes safe password practices. This project demonstrates core security awareness principles such as strong password policies and secure form handling.

🌐 **Live Demo:** [djangopasswordstrengthchecker.onrender.com](https://djangopasswordstrengthchecker.onrender.com/)

---

## 🎯 Project Objective

This project is designed to promote **cyber hygiene** and highlight the importance of **strong password creation** — a fundamental aspect of cybersecurity. It also demonstrates basic Django security features such as CSRF protection and input validation.

---

## 🛡️ Cybersecurity Highlights

- ✅ Enforces awareness about **weak passwords**, which are a common vulnerability.
- 🔒 Uses Django's built-in **CSRF protection** to prevent cross-site request forgery.
- 🛑 Discourages poor password choices by analyzing:
  - Length
  - Use of digits
  - Use of uppercase/lowercase letters
  - Presence of special characters
- 🎯 Educates users with visual feedback: Weak (🔴), Medium (🟠), Strong (🟢)

---

## 🚀 Features

- Password input with show/hide toggle
- Inline password strength analysis and visual feedback
- Simple, mobile-friendly interface using inline CSS
- Deployed live on Render for easy access

---

## 🧠 How It Works

1. User enters a password.
2. Backend logic checks the password against multiple criteria.
3. Based on the result, the app displays strength with appropriate color coding:
   - **Weak** (red): Short, missing character diversity
   - **Medium** (orange): Moderate length, partial diversity
   - **Strong** (green): Long, diverse characters
