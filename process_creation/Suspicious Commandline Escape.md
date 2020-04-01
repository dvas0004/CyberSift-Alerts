# Suspicious Commandline Escape
### Description

Detects suspicious process that use escape characters.

-------------------
### Severity

Low

-------------------
<!---
### Detailed Information

- Why is this alert triggered?
- What are the typical causes that generate this alert? (e.g. port scans, unusual file access activity, etc...)
- Which corroborating information should be looked up?
- Any supporting queries to get more information?
- Any supporting visualizations to get more information?

-------------------
--->
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
