# Scheduled Task Creation
### Description

Detects the creation of scheduled tasks in user session.

-------------------
### Severity

- Low

-------------------

### Detailed Information

Triggers on scheduled tasks being created using schtasks.exe under any user other than NT_AUTHORITY\SYSTEM

-------------------

### Possible causes of false positives

- Administrative activity
- Software installation

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
