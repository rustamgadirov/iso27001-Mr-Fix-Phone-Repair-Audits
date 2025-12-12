## Finding Title: Passwords Stored in Plain Text on Office Computer  
### ISO 27001 Control: A.10 – Cryptographic Controls

**Issue:**  
Employees are storing passwords for office accounts in a plain text file on the office computer. This practice exposes sensitive credentials without any cryptographic protection.

**Evidence:**  
During the manager’s investigation, a file named “passwords” was found on the desktop. The contents showed multiple account passwords written in clear, unencrypted text.

**Impact:**  
Storing passwords in plain text significantly increases the risk of unauthorized access, data exposure, identity theft, and financial loss. This is noncompliant with ISO 27001 A.10 requirements, which mandate appropriate use of cryptographic controls to protect sensitive information.

**Recommendation:**  
Implement a secure, encrypted password management tool for all staff (such as Bitwarden or 1Password). Ensure encryption keys are stored securely and restrict access only to authorized personnel. Remove all unencrypted password files immediately.
