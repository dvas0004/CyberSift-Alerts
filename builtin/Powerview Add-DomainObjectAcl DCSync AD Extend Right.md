# Powerview Add-DomainObjectAcl DCSync AD Extend Right
### Description

Backdooring domain object to grant the rights associated with DCSync to a regular user or machine account using Powerview\Add-DomainObjectAcl DCSync Extended Right cmdlet, 
will allow to re-obtain the pwd hashes of any user/computer

-------------------
### Severity

Critical

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

- https://twitter.com/menasec1/status/1111556090137903104
- https://www.specterops.io/assets/resources/an_ace_up_the_sleeve.pdf

-------------------
### Supported Log Sources

- windows security

-------------------
