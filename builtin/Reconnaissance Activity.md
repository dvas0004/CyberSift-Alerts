# Reconnaissance Activity
### Description

Detects activity as "net user administrator /domain" and "net group domain admins /domain"

-------------------
### Severity

- High
<!---
-------------------
### Detailed Information

- Why is this alert triggered?
- What are the typical causes that generate this alert? (e.g. port scans, unusual file access activity, etc...)
- Which corroborating information should be looked up?
- Any supporting queries to get more information?
- Any supporting visualizations to get more information?
--->
-------------------
### Possible causes of false positives

  - Administrator activity
  - Penetration tests

-------------------
### References

  - https://findingbad.blogspot.de/2017/01/hunting-what-does-it-look-like.html

-------------------
### Supported Log Sources

- windows security

-------------------
