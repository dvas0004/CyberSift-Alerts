# Mimikatz DC Sync
### Description

Detects Mimikatz DC sync security events

-------------------
### Severity

- Critical

-------------------

### Detailed Information

Allows detection of the DCSync command from Mimikatz; used to impersonate a Domain Controller on a Windows Active Directory network.

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/gentilkiwi/status/1003236624925413376
- https://gist.github.com/gentilkiwi/dcc132457408cf11ad2061340dcb53c2
- https://attack.stealthbits.com/privilege-escalation-using-mimikatz-dcsync

-------------------
### Supported Log Sources

- windows security

-------------------
