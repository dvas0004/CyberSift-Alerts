# Possible Process Hollowing Image Loading
### Description

Detects Loading of samlib.dll, WinSCard.dll from untypical process e.g. through process hollowing by Mimikatz.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon event Image loaded (event id 7) where 'Image' is notepad.exe and the 'ImageLoaded' (ie: the DLL being loaded is) one of:
  - samlib.dll
  - WinSCard.dll

-------------------

### Possible causes of false positives

- Very likely, needs more tuning

-------------------
### References

- https://cyberwardog.blogspot.com/2017/03/chronicles-of-threat-hunter-hunting-for.html

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
