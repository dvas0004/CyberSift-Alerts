# Hijack legit RDP session to move laterally
### Description

Detects the usage of tsclient share to place a backdoor on the RDP source machine's startup folder.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on sysmon event FileCreate (event id 11) where the 'TargetFileName' attribute (ie: the path of the file created) fits '*\Microsoft\Windows\Start Menu\Programs\Startup\*' 

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
