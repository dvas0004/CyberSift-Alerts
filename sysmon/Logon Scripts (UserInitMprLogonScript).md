# Logon Scripts (UserInitMprLogonScript)
### Description

Detects creation or execution of UserInitMprLogonScript persistence method.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers when:
  - process is created with userinit.exe as parent image unless process is explorer.exe created usingmnetlogon.bat script
OR
  - Process is created (sysmon event id 1)
  - File is created (sysmon event id 11)
  - Registry Object Created Or Deleted (event id 12)
  - Registry Value Set (event id 13)
  - Registry Key renamed (event id 14)
  AND
  - The command causing one or more of the above contains the keyword UserInitMprLogonScript.
  
-------------------

### Possible causes of false positives

- exclude legitimate logon scripts
- penetration tests, red teaming

-------------------
### References

- https://attack.mitre.org/techniques/T1037/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
