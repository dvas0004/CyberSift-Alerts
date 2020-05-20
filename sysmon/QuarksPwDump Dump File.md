# QuarksPwDump Dump File
### Description

Detects a dump file written by QuarksPwDump password dumper

-------------------
### Severity

Critical

-------------------

### Detailed Information

Triggers on Sysmon event 'FileCreate' (ID 11) where attribute 'TargetFilename' (ie: the path of the file being created) fits:
  - '*\AppData\Local\Temp\SAM-*.dmp*'

-------------------

### Possible causes of false positives

=> What could cause this alert to mistakenly get generated? For example: <=
- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)

-------------------
### References

- https://jpcertcc.github.io/ToolAnalysisResultSheet/details/QuarksPWDump.htm

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
