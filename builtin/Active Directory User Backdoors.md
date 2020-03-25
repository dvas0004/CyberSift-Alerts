# Active Directory User Backdoors
### Description

Detects scenarios where one can control another users or computers account without having to use their credentials.

-------------------
### Severity

High

-------------------
### Detailed Information
Definitions:
  - 'Requirements: Audit Policy : Account Management > Audit User Account Management, Group Policy : Computer Configuration\Windows Settings\Security Settings\Advanced Audit Policy Configuration\Audit Policies\Account Management\Audit User Account Management'
  - 'Requirements: Audit Policy : DS Access > Audit Directory Service Changes, Group Policy : Computer Configuration\Windows Settings\Security Settings\Advanced Audit Policy Configuration\Audit Policies\DS Access\Audit Directory Service Changes'

-------------------

### Possible causes of false positives

Unknown

-------------------

### References

- https://msdn.microsoft.com/en-us/library/cc220234.aspx
- https://adsecurity.org/?p=3466
- https://www.harmj0y.net/blog/redteaming/another-word-on-delegation/

-------------------
### Supported Log Sources

- windows security

-------------------
