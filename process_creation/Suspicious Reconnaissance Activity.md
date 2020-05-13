# Suspicious Reconnaissance Activity
### Description

Detects suspicious command line activity on Windows systems.

-------------------
### Severity

Medium

-------------------

### Detailed Information
Triggers on one of the following commands:
  - net group "domain admins" /domain
  - net localgroup administrators

-------------------

### Possible causes of false positives

- Inventory tool runs
- Penetration tests
- Administrative activity

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
