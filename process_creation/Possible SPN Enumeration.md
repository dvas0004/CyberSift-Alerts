# Possible SPN Enumeration
### Description

Detects Service Principal Name Enumeration used for Kerberoasting.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on setspn.exe with '-q' as parameter.

-------------------

### Possible causes of false positives

- Administrator Activity

-------------------
### References

- https://p16.praetorian.com/blog/how-to-use-kerberoasting-t1208-for-privilege-escalation

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
