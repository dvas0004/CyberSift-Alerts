# Rundll32 Internet Connection
### Description

Detects a rundll32 that communicates with public IP addresses.

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

- Communication to other corporate systems that use IP addresses from public address spaces

-------------------
### References

- https://www.hybrid-analysis.com/sample/759fb4c0091a78c5ee035715afe3084686a8493f39014aea72dae36869de9ff6?environmentId=100

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
