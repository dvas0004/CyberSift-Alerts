# Suspicious WMI execution
### Description

Detects WMI executing suspicious commands.

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

    - Will need to be tuned
    - If using Splunk, I recommend | stats count by Computer,CommandLine following for easy hunting by Computer/CommandLine.

-------------------
### References

    - https://digital-forensics.sans.org/blog/2010/06/04/wmic-draft/
    - https://www.hybrid-analysis.com/sample/4be06ecd234e2110bd615649fe4a6fa95403979acf889d7e45a78985eb50acf9?environmentId=1
    - https://blog.malwarebytes.com/threat-analysis/2016/04/rokku-ransomware/
    
-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
