# Microsoft Binary Suspicious Communication Endpoint
### Description

Detects an executable in the Windows folder accessing suspicious domains.

-------------------
### Severity

High

-------------------
### Detailed Information
Triggers on Sysmon Event ID 3 (Network connection) where DestinationHostname fits one of:
  - '*dl.dropboxusercontent.com'
  - '*.pastebin.com'
<br>AND<br>
Image field fits: 'C:\Windows\*' (ie: connecting process is an executable inside the Windows directory)

-------------------
### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/M_haggis/status/900741347035889665
- https://twitter.com/M_haggis/status/1032799638213066752

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
