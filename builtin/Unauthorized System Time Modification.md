# Unauthorized System Time Modification
### Description

Detect scenarios where a potentially unauthorized application or user is modifying the system time.

-------------------
### Severity

- High

-------------------

### Detailed Information

Events:
  - 4616 The system time was changed

Exceptions made for when system time is changed by an instance of svchost.exe running under NT AUTHORITY\Local Service.

-------------------

### Possible causes of false positives

- HyperV or other virtualization technologies with binary not listed in filter portion of detection

-------------------
### References

- Private Cuckoo Sandbox (from many years ago, no longer have hash, NDA as well)
- Live environment caused by malware

-------------------
### Supported Log Sources

- windows security

-------------------
