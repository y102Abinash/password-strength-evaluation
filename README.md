# password-strength-evaluation
Task 6: Strong Password Creation &amp; Evaluation using Kali Linux cracklib-check and passwordmeter.com
# Password Strength Testing – Offline & Online

This project demonstrates how to test the strength of a password using both **offline** (Kali Linux cracklib-check) and **online** (passwordmeter.com) methods.

---

## 📌 Overview

Password security is critical in protecting personal and organizational data. Weak passwords can be easily guessed or cracked.  
In this project, we use:
1. **Offline strength test** → using `cracklib-check` in Kali Linux.
2. **Online strength test** → using [Password Meter](https://passwordmeter.com).

---

## 🔧 Tools Used

- **Kali Linux** – penetration testing OS
- **cracklib-check** – checks passwords against common dictionary words
- **passwordmeter.com** – evaluates password strength based on multiple parameters

---

## 📥 Installation (Offline Method – Kali Linux)

### Step 1: Update Package List
```bash
sudo apt update
sudo apt install libcrack2 cracklib-runtime -y



