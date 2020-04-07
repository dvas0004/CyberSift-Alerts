# AD Privileged Users or Groups Reconnaissance
### Description

Detect priv users or groups recon based on 4661 eventid and known privileged users or groups SIDs

-------------------
### Severity

High

-------------------
### Detailed Information

Look for event 4661 with Message body containing known AD privileged groups/accounts SID values.

-------------------
### Possible causes of false positives

=> What could cause this alert to mistakenly get generated? For example: <=
- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)

-------------------
--->
### References

- https://blog.menasec.net/2019/02/threat-hunting-5-detecting-enumeration.html

-------------------
### Supported Log Sources

- windows security

-------------------
