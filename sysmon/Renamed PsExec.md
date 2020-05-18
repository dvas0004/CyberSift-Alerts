# Renamed PsExec
### Description

Detects the execution of a renamed PsExec often used by attackers or malware. 

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon event where attribute 'Description' has value : 'Execute processes remotely' and Product has value : 'Sysinternals PsExec'  and 'Image' (originating process) is NOT 'PsExec.exe'.

-------------------

### Possible causes of false positives

- Software that illegaly integrates PsExec in a renamed form
- Administrators that have renamed PsExec and no one knows why

-------------------
### References

- https://www.trendmicro.com/vinfo/hk-en/security/news/cybercrime-and-digital-threats/megacortex-ransomware-spotted-attacking-enterprise-networks

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
