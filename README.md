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
2. Navigating to **Computer Configuration** 
3. Selecting **Windows Settings > Security Settings > Account Policy**
4. Selecting **Password Policy & View Default Settings (Very Weak)**
5. Viewing the changes I made (A bit strict but normal in Federal working envrionments)
6. Selecting **Account Lockout Policy**
7. Viewing the changes I made

---

## ✅ Outcome
By applying these changes:
- Passwords are now stronger and harder to guess
- Accounts are protected against brute-force attacks
- Overall login security is significantly improved

---

## 📂 How to Use This Repo
- Review the screenshots for step-by-step guidance
- Apply similar settings in your own environment using the Group Policy Editor
- Adapt thresholds and requirements to match your organization’s security needs

---

## ⚠️ Notes
- These settings apply to **Windows environments** using Group Policy Editor
- Always balance security with usability to avoid locking out legitimate users
- Regularly review and update policies as threats evolve
