# Mimikatz Use
### Description

This method detects mimikatz keywords in different Eventlogs. 
(Some of them only appear in older Mimikatz version that are however still used by different threat groups)
-------------------
### Severity

- Critical

-------------------
### Detailed Information

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

- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)

-------------------
### References
    - Naughty administrators
    - Penetration test
    
-------------------
### Supported Log Sources

- windows

-------------------
