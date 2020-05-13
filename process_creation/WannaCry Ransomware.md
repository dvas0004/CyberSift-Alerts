# WannaCry Ransomware
### Description

Detects WannaCry ransomware activity.

-------------------
### Severity

- Critical

-------------------
### Detailed Information

Triggers on one of the following executables running:

  - '*\tasksche.exe'
  - '*\mssecsvc.exe'
  - '*\taskdl.exe'
  - '*\@WanaDecryptor@*'
  - '*\WanaDecryptor*'
  - '*\taskhsvc.exe'
  - '*\taskse.exe'
  - '*\111.exe'
  - '*\lhdfrgui.exe'
  - '*\diskpart.exe'
  - '*\linuxnew.exe'
  - '*\wannacry.exe'

Or one of the following commandline instructions:

  - '*icacls * /grant Everyone:F /T /C /Q*'
  - '*bcdedit /set {default} recoveryenabled no*'
  - '*wbadmin delete catalog -quiet*'
  - '*@Please_Read_Me@.txt*'
  
-------------------
### Possible causes of false positives

- Diskpart.exe usage to manage partitions on the local hard drive

-------------------
### References

- https://www.hybrid-analysis.com/sample/ed01ebfbc9eb5bbea545af4d01bf5f1071661840480439c6e5babe8e080e41aa?environmentId=100

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
