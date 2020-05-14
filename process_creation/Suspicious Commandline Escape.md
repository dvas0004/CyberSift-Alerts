# Suspicious Commandline Escape
### Description

Detects suspicious process that use escape characters.

-------------------
### Severity

Low

-------------------

### Detailed Information

Triggers on command line commands containing:
  - <TAB>
  - ^h^t^t^p
  - h"t"t"p



-------------------

### Possible causes of false positives

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://twitter.com/vysecurity/status/885545634958385153
- https://twitter.com/Hexacorn/status/885553465417756673
- https://twitter.com/Hexacorn/status/885570278637678592
- https://www.fireeye.com/blog/threat-research/2017/06/obfuscation-in-the-wild.html
- http://www.windowsinspired.com/understanding-the-command-line-string-and-arguments-received-by-a-windows-program/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
