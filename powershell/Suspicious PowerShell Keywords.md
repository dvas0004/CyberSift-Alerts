# Suspicious PowerShell Keywords
### Description

Detects keywords that could indicate the use of some PowerShell exploitation framework.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers On Keywords:
  - System.Reflection.Assembly.Load

-------------------

### Possible causes of false positives

- Penetration tests

-------------------
### References

- https://posts.specterops.io/entering-a-covenant-net-command-and-control-e11038bcf462

-------------------
### Supported Log Sources

- Windows Powershell

-------------------
