# SWIFT Abnormal Login Time
### Description

A user has logged into SWIFT at an unusual time.

-------------------
### Severity

Medium

-------------------
### Detailed Information

When a user logs in for the first time they get assigned to one of the following categories:

WORKDAY
WEEKEND
DAY (7am-7pm)
NIGHT

If they log in at a different time and are assigned to a different category, this alert is triggered.

-------------------
### Possible causes of false positives

=> What could cause this alert to mistakenly get generated? For example: <=
- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)

-------------------
### References

=> List of links and external sources which support the information for this alert. Any applicable [MITRE](https://attack.mitre.org/) information should be added here as well <=

-------------------
### Supported Log Sources

=> Insert supported log sources here, for example: <=
- windows application
- windows security
- firewall

-------------------
