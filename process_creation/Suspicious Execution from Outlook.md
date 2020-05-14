# Suspicious Execution from Outlook
### Description

Detects EnableUnsafeClientMailRules used for Script Execution from Outlook.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on EnableUnsafeClientMailRules being activated from command line or an command prompt with outlook.exe as parent process running an executable file.

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://github.com/sensepost/ruler
- https://www.fireeye.com/blog/threat-research/2018/12/overruled-containing-a-potentially-destructive-adversary.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
