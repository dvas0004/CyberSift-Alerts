# Executables Started in Suspicious Folder
### Description

Detects process starts of binaries from a suspicious folder.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on execution of binaries from the following folders:
  - C:\PerfLogs\\*
  - C:\$Recycle.bin\\*
  - C:\Intel\Logs\\*
  - C:\Users\Default\\*
  - C:\Users\Public\\*
  - C:\Users\NetworkService\\*
  - C:\Windows\Fonts\\*
  - C:\Windows\Debug\\*
  - C:\Windows\Media\\*
  - C:\Windows\Help\\*
  - C:\Windows\addins\\*
  - C:\Windows\repair\\*
  - C:\Windows\security\\*
  - '*\RSA\MachineKeys\\*'
  - C:\Windows\system32\config\systemprofile\\*

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://github.com/mbevilacqua/appcompatprocessor/blob/master/AppCompatSearch.txt
- https://www.secureworks.com/research/bronze-butler-targets-japanese-businesses
- https://www.crowdstrike.com/resources/reports/2019-crowdstrike-global-threat-report/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
