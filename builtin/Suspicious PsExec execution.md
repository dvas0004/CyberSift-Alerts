# Suspicious PsExec execution
### Description

Detects execution of psexec or paexec with renamed service name,
this rule helps to filter out the noise if psexec is used for legit purposes or if attacker uses a different psexec client other than sysinternal one.

-------------------
### Severity

- High

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

-None observed so far.
-Unknown

-------------------
### References

- https://blog.menasec.net/2019/02/threat-hunting-3-detecting-psexec.html

-------------------
### Supported Log Sources

- windows security

-------------------
