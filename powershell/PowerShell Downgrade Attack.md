# PowerShell Downgrade Attack
### Description

Detects PowerShell downgrade attack by comparing the host versions with the actually used engine version 2.0

-------------------
### Severity

- Medium

-------------------

### Detailed Information

Event ID:
  - 400 Engine state is changed from None to Available
 
-------------------

### Possible causes of false positives

- Penetration Test
- Unknown

-------------------
### References

- http://www.leeholmes.com/blog/2017/03/17/detecting-and-preventing-powershell-downgrade-attacks/

-------------------
### Supported Log Sources

- Windows Powershell Classic

-------------------
