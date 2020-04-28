# Cmdkey Cached Credentials Recon
### Description

Detects usage of cmdkey to look for cached credentials.

-------------------
### Severity

- Low

-------------------

### Detailed Information

Triggers On Command Line Instructions:
  - *\cmdkey.exe * /list *

-------------------

### Possible causes of false positives

 - Legitimate administrative tasks.

-------------------
### References

  - https://www.peew.pw/blog/2017/11/26/exploring-cmdkey-an-edge-case-for-privilege-escalation
  - https://technet.microsoft.com/en-us/library/cc754243(v=ws.11).aspx
  
-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
