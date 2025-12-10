## Finding Title: Unauthorized Assignment of Administrator Privileges  
### ISO 27001 Control: A.9 – User Access Management

**Issue:**  
A technician modified their own account to obtain Administrator privileges on the office computer. This grants unrestricted system access beyond their job responsibilities.

**Evidence:**  
System access logs show privilege escalation from standard user to Administrator under the technician’s account. Staff also observed changes to software settings and customer data without approved authorization.

**Impact:**  
Unauthorized administrator rights increase the risk of system misuse, data modification, malware installation, and financial loss. This is a violation of ISO 27001 A.9 access control requirements, which require privileges to be granted only upon formal approval.

**Recommendation:**  
Remove Administrator access from the technician’s account immediately. Implement a privileged access approval process, ensuring that elevated rights must be documented, reviewed, and authorized by management. Enable logging and monthly access reviews for all admin accounts.
