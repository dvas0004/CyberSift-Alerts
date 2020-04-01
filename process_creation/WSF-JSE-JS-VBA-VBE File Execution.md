# WSF/JSE/JS/VBA/VBE File Execution
### Description

Detects suspicious file execution by wscript and cscript.

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

- Will need to be tuned. I recommend adding the user profile path in CommandLine if it is getting too noisy.

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
