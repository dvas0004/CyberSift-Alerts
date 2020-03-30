# Netsh RDP Port Forwarding
### Description

Detects netsh commands that configure a port forwarding of port 3389 used for RDP

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
--->
### Possible causes of false positives

- Legitimate administration

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2019/01/bypassing-network-restrictions-through-rdp-tunneling.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
