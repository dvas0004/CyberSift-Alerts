# Detects Local User Creation
### Description

Detects local user creation on windows servers, which shouldn't happen in an Active Directory environment.
Apply this Sigma Use Case on your windows server logs and not on your DC logs.

-------------------
### Severity

- Low

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

- Domain Controller Logs
- Local accounts managed by privileged account management tools

-------------------
### References

- https://patrick-bareiss.com/detecting-local-user-creation-in-ad-with-sigma/

-------------------
### Supported Log Sources

- windows security

-------------------
