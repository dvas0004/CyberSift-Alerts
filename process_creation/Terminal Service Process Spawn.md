# Terminal Service Process Spawn
### Description

Detects a process spawned by the terminal service server process.
(This could be an indicator for an exploitation of CVE-2019-0708)

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers where a process is created having parent process fitting the pattern: '*\svchost.exe*termsvcs'
If the created process is rdpclip.exe, this rule does not trigger.

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
