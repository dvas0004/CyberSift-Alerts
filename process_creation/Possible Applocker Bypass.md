# Possible Applocker Bypass
### Description

Detects execution of executables that can be used to bypass Applocker whitelisting

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
- Using installutil to add features for .NET applications (primarly would occur in developer environments)

-------------------
### References

- https://github.com/subTee/ApplicationWhitelistBypassTechniques/blob/master/TheList.txt
- https://room362.com/post/2014/2014-01-16-application-whitelist-bypass-using-ieexec-dot-exe/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
