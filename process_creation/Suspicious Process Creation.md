# Suspicious Process Creation
### Description

Detects suspicious process starts on Windows systems based on keywords.

-------------------
### Severity

Medium

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

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://www.swordshield.com/2015/07/getting-hashes-from-ntds-dit-file/
- https://www.youtube.com/watch?v=H3t_kHQG1Js&feature=youtu.be&t=15m35s
- https://winscripting.blog/2017/05/12/first-entry-welcome-and-uac-bypass/
- https://twitter.com/subTee/status/872244674609676288
- https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/remote-tool-examples
- https://tyranidslair.blogspot.ca/2017/07/dg-on-windows-10-s-executing-arbitrary.html
- https://www.trustedsec.com/2017/07/new-tool-release-nps_payload/
- https://subt0x10.blogspot.ca/2017/04/bypassing-application-whitelisting.html
- https://gist.github.com/subTee/7937a8ef07409715f15b84781e180c46#file-rat-bat
- https://twitter.com/vector_sec/status/896049052642533376
- http://security-research.dyndns.org/pub/slides/FIRST-TC-2018/FIRST-TC-2018_Tom-Ueltschi_Sysmon_PUBLIC.pdf

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
