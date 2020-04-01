# Suspicious Rundll32 Activity
### Description

Detects suspicious process related to rundll32 based on arguments.

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

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- http://www.hexacorn.com/blog/2017/05/01/running-programs-via-proxy-jumping-on-a-edr-bypass-trampoline/
- https://twitter.com/Hexacorn/status/885258886428725250
- https://gist.github.com/ryhanson/227229866af52e2d963cf941af135a52

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
