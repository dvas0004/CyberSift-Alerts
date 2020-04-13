# Mimikatz DC Sync
### Description

Detects Mimikatz DC sync security events

-------------------
### Severity

- Critical

-------------------

### Detailed Information

Allows detection of the DCSync command from Mimikatz; used to impersonate a Domain Controller on a Windows Active Directory network. This command can be used to retrieve hashed account passwords which can be then used in a Pass-The-Hash attack to create forged Kerberos tickets to access resources on the Active Directory network.

Triggered on detection of the following events from any users with SIDs not having the SID authority of NT Authority\

  - 4624 Succesful login attempt.
  - 4742 Computer Account is changed.
  - 4662 User accesses an active directory object.

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
