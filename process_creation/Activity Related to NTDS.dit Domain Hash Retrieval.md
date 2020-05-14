# Activity Related to NTDS.dit Domain Hash Retrieval
### Description

Detects suspicious commands that could be related to activity that uses volume shadow copy to steal and retrieve hashes from the NTDS.dit file remotely

-------------------
### Severity

High

-------------------

### Detailed Information
Triggers on a command fitting one of the following wildcard patterns being run:
  - vssadmin.exe Delete Shadows
  - 'vssadmin create shadow /for=C:'
  - copy \\?\GLOBALROOT\Device\\*\windows\ntds\ntds.dit
  - copy \\?\GLOBALROOT\Device\\*\config\SAM
  - 'vssadmin delete shadows /for=C:'
  - 'reg SAVE HKLM\SYSTEM '
  - esentutl.exe /y /vss *\ntds.dit*

-------------------

### Possible causes of false positives

- Administrative activity

-------------------
### References

- https://www.swordshield.com/2015/07/getting-hashes-from-ntds-dit-file/
- https://room362.com/post/2013/2013-06-10-volume-shadow-copy-ntdsdit-domain-hashes-remotely-part-1/
- https://www.trustwave.com/Resources/SpiderLabs-Blog/Tutorial-for-NTDS-goodness-(VSSADMIN,-WMIS,-NTDS-dit,-SYSTEM)/
- https://securingtomorrow.mcafee.com/mcafee-labs/new-teslacrypt-ransomware-arrives-via-spam/
- https://dfironthemountain.wordpress.com/2018/12/06/locked-file-access-using-esentutl-exe/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
