# Bitsadmin Download
### Description

Detects usage of bitsadmin downloading a file

-------------------
### Severity

Medium

-------------------

### Detailed Information

Events:
  - Comandline 'bitsadmin.exe /transfer'
  
-------------------

### Possible causes of false positives

- Some legitimate apps use this, but limited.

-------------------
### References

- https://blog.netspi.com/15-ways-to-download-a-file/#bitsadmin
- https://isc.sans.edu/diary/22264

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
