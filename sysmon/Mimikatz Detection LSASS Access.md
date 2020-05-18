# Mimikatz Detection LSASS Access
### Description

Detects process access to LSASS which is typical for Mimikatz (0x1000 PROCESS_QUERY_ LIMITED_INFORMATION, 0x0400 PROCESS_QUERY_ INFORMATION, 0x0010 PROCESS_VM_READ)

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon Event ID 10 (ProcessAccess) where process accessed is lsass.exe and Granted Acces is '0x410'.

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://onedrive.live.com/view.aspx?resid=D026B4699190F1E6!2843&ithint=file%2cpptx&app=PowerPoint&authkey=!AMvCRTKB_V1J5ow

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
