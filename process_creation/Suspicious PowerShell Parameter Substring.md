# Suspicious PowerShell Parameter Substring
### Description

Detects suspicious PowerShell invocation with a parameter substring

-------------------
### Severity

High

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

- Penetration Tests

-------------------
### References

- http://www.danielbohannon.com/blog-1/2017/3/12/powershell-execution-argument-obfuscation-how-it-can-make-detection-easier

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
