# Suspicious Use of Procdump
### Description

Detects suspicious uses of the SysInternals Procdump utility by using a special command line parameter in combination with the lsass.exe process. This
way we're also able to catch cases in which the attacker has renamed the procdump executable.

-------------------
### Severity

Medium

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

- Unlikely, because no one should dump an lsass process memory
- Another tool that uses the command line switches of Procdump

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
