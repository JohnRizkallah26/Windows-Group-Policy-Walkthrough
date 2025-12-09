# Windows Group Policy Editor Walkthrough

This walkthrough documents the steps taken to harden login settings using the Windows Group Policy Editor. The repository includes **7 screenshots** that illustrate each stage of the configuration process.

## 🎯 Objectives
- Strengthen password requirements
- Configure account lockout policies
- Improve overall login security posture

---

## 🔐 Password Policy Changes
The password policy was updated to enforce stricter rules:
- **Minimum password length** increased
- **Password complexity** enabled (requiring uppercase, lowercase, numbers, and special characters)
- **Maximum password age** reduced to ensure regular password changes
- **Password history** lengthened to prevent reuse of recent passwords

These changes ensure that user accounts are protected by stronger, more resilient passwords.

---

## 🚫 Account Lockout Policy Changes
The account lockout policy was configured to mitigate brute-force login attempts:
- **Account lockout threshold** set to a lower number of failed attempts
- **Lockout duration** increased to slow down repeated attacks
- **Reset account lockout counter** adjusted to balance usability and security

This configuration helps prevent unauthorized access by locking accounts after repeated failed login attempts.

---

## 📸 Screenshots
The repository contains **7 screenshots** showing:
1. Opening the Group Policy Editor
2. Navigating to **Account Policies → Password Policy**
3. Configuring minimum password length
4. Enabling password complexity requirements
5. Navigating to **Account Policies → Account Lockout Policy**
6. Setting the account lockout threshold
7. Configuring lockout duration and reset counter

---

## ✅ Outcome
By applying these
