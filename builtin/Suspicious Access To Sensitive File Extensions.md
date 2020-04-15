# Suspicious Access To Sensitive File Extensions
### Description

Detects known sensitive file extensions.

-------------------
### Severity

- High

-------------------

### Detailed Information

Event:
  - 5145 A Network Share Object Was Checked To See Whether Client Can Be Granted Desired Access.
  
Triggers on access to files with the following extensions:
  - '*.pst'
  - '*.ost'
  - '*.msg'
  - '*.nst'
  - '*.oab'
  - '*.edb'
  - '*.nsf' 
  - '*.bak'
  - '*.dmp'
  - '*.kirbi'
  - '*\ntds.dit'
  - '*\groups.xml'
- '*.rdp'

-------------------

### Possible causes of false positives

- Help Desk operator doing backup or re-imaging end user machine or pentest or backup software

-------------------
### References

  - None
  
-------------------
### Supported Log Sources

- windows security

-------------------
