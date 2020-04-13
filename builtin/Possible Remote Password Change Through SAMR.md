# Possible Remote Password Change Through SAMR
### Description

Detects a possible remote NTLM hash change through SAMR API SamiChangePasswordUser() or SamSetInformationUser(). 
"Audit User Account Management" in "Advanced Audit Policy Configuration" has to be enabled in your local security policy / GPO to see this events.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

Events:
  - 5145 Network Share Object Accessed
  - 4738 User Account Was Changed


-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- None

-------------------
### Supported Log Sources

- windows security

-------------------
