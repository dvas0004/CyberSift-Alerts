# SID history failure
### Description

An attempt to add SID History to an account failed.

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
### Possible causes of false positives

=> What could cause this alert to mistakenly get generated? For example: <=
- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)

-------------------
--->
### References

- https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/plan/appendix-l--events-to-monitor 
- https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/event-4766#security-monitoring-recommendations

-------------------
### Supported Log Sources

- windows security

-------------------
