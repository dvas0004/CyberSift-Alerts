# First Time Seen Remote Named Pipe
### Description

This detection excludes known namped pipes accessible remotely and notify on newly observed ones, 
may help to detect lateral movement and remote exec using named pipes.

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

- update the excluded named pipe to filter out any newly observed legit named pipe

-------------------
### References

- https://twitter.com/menasec1/status/1104489274387451904

-------------------
### Supported Log Sources

- Windows Security

-------------------
