# Enabled User Right in AD to Control User Objects
### Description

Detects scenario where if a user is assigned the SeEnableDelegationPrivilege right in Active Directory it would allow control of other AD user objects.

-------------------
### Severity

High

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

Unknown

-------------------
### References

- https://www.harmj0y.net/blog/activedirectory/the-most-dangerous-user-right-you-probably-have-never-heard-of/

-------------------
### Supported Log Sources

- windows security

-------------------
