# PowerShell Rundll32 Remote Thread Creation
### Description

Detects PowerShell remote thread creation in Rundll32.exe .

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon event CreateRemoteThread (Event ID 8) where 'SourceImage' is powershell.exe and 'TargetImage' is rundll32.exe

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2018/06/bring-your-own-land-novel-red-teaming-technique.html

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
