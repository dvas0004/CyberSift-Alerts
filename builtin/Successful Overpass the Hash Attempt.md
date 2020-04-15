# Successful Overpass the Hash Attempt
### Description

Detects successful logon with logon type 9 (NewCredentials) which matches the Overpass the Hash behavior of e.g Mimikatz's sekurlsa::pth module.

-------------------
### Severity

- High

-------------------

### Detailed Information

Events
  - 4624 Succesful account log on.

Triggers on logon type: 9 - New Credentials (https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/event-4624) with logon process name: 'seclogo'.


-------------------

### Possible causes of false positives

- Runas command-line tool using /netonly parameter

-------------------
### References

- https://cyberwardog.blogspot.de/2017/04/chronicles-of-threat-hunter-hunting-for.html

-------------------
### Supported Log Sources

- windows security

-------------------
