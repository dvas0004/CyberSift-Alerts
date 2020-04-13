# Mimikatz Use
### Description

This method detects mimikatz keywords in different Eventlogs. 
(Some of them only appear in older Mimikatz version that are however still used by different threat groups)
-------------------
### Severity

- Critical

-------------------
### Detailed Information

Detects keywords that denote the use of the Mimikatz pentesting tool in event logs.
Keywords:
  - "* mimikatz *"
  - "* mimilib *"
  - "* <3 eo.oe *"
  - "* eo.oe.kiwi *"
  - "* privilege::debug *"
  - "* sekurlsa::logonpasswords *"
  - "* lsadump::sam *"
  - "* mimidrv.sys *"

-------------------
### Possible causes of false positives

- Naughty administrators
- Penetration test

-------------------
### References

  - https://www.ethicalhackers.co.za/post/mimikatz_cheatsheet/
    
-------------------
### Supported Log Sources

- Windows

-------------------
