# Weak Encryption Enabled and Kerberoast
### Description

Detects scenario where weak encryption is enabled for a user profile which could be used for hash/password cracking.

-------------------
### Severity

High

-------------------
### Detailed Information

Definitions
  -'Requirements: Audit Policy : Account Management > Audit User Account Management, Group Policy : Computer Configuration\Windows Settings\Security Settings\Advanced Audit Policy Configuration\Audit Policies\Account Management\Audit User Account Management'

-------------------
### Possible causes of false positives

Unknown

-------------------
### References

- https://adsecurity.org/?p=2053
- https://www.harmj0y.net/blog/activedirectory/roasting-as-reps/

-------------------
### Supported Log Sources

- windows security

-------------------
