# Suspicious Scripting in a WMI Consumer
### Description

Detects suspicious scripting in WMI Event Consumers 

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

- Administrative scripts

-------------------
### References

- https://in.security/an-intro-into-abusing-and-identifying-wmi-event-subscriptions-for-persistence/
- https://github.com/Neo23x0/signature-base/blob/master/yara/gen_susp_lnk_files.yar#L19

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
