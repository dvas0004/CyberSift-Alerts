# Terminal Service Process Spawn
### Description

Detects a process spawned by the terminal service server process (this could be an indicator for an exploitation of CVE-2019-0708)

-------------------
### Severity

- High

-------------------

### Detailed Information

Detects '*\sdbinst.exe' ran with parameters fitting '*\AppPatch\\*}.sdb*'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://securingtomorrow.mcafee.com/other-blogs/mcafee-labs/rdp-stands-for-really-do-patch-understanding-the-wormable-rdp-vulnerability-cve-2019-0708/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
