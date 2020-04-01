# Net.exe Execution
### Description

Detects execution of Net.exe, whether suspicious or benign.

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

- Will need to be tuned. If using Splunk, I recommend | stats count by Computer,CommandLine following the search for easy hunting by computer/CommandLine.

-------------------
### References

- https://pentest.blog/windows-privilege-escalation-methods-for-pentesters/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
