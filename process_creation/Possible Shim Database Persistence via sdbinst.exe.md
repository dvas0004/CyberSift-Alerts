# Possible Shim Database Persistence via sdbinst.exe
### Description

Detects execution of sdbinst writing to default shim database path C:\Windows\AppPatch\*

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on sdbinst.exe run with parameters fitting '*\AppPatch\\*}.sdb*'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2017/05/fin7-shim-databases-persistence.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
