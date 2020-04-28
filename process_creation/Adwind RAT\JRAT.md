# Adwind RAT / JRAT
### Description

Detects javaw.exe in AppData folder as used by Adwind / JRAT.

-------------------
### Severity

- High

-------------------

### Detailed Information

Events:
  - 11 File Create
    Triggers On Files Created With Names:
      - '*\AppData\Roaming\Oracle\bin\java*.exe'
      - '*\Retrive*.vbs
  
  - 13 Registry Value Set
    Triggers On Setting Registry Keys Fitting:
      - \REGISTRY\MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run*
    With Values Fitting:  
      - %AppData%\Roaming\Oracle\bin\\*
      
  - Process Creation
    Triggers on Processes Created With Names Fitting:
      - '*\AppData\Roaming\Oracle*\java*.exe *'
      - '*cscript.exe *Retrive*.vbs *'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://www.hybrid-analysis.com/sample/ba86fa0d4b6af2db0656a88b1dd29f36fe362473ae8ad04255c4e52f214a541c?environmentId=100
- https://www.first.org/resources/papers/conf2017/Advanced-Incident-Detection-and-Threat-Hunting-using-Sysmon-and-Splunk.pdf

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
