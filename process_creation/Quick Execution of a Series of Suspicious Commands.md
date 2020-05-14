# Quick Execution of a Series of Suspicious Commands
### Description

Detects multiple suspicious process in a limited timeframe

-------------------
### Severity

- Low

-------------------

### Detailed Information
Triggers on more than 5 of the following processes in a 5 minute timespan on the same machine:
  - arp.exe
  - at.exe
  - attrib.exe
  - cscript.exe
  - dsquery.exe
  - hostname.exe
  - ipconfig.exe
  - mimikatz.exe
  - nbtstat.exe
  - net.exe
  - netsh.exe
  - nslookup.exe
  - ping.exe
  - quser.exe
  - qwinsta.exe
  - reg.exe
  - runas.exe
  - sc.exe
  - schtasks.exe
  - ssh.exe
  - systeminfo.exe
  - taskkill.exe
  - telnet.exe
  - tracert.exe
  - wscript.exe
  - xcopy.exe
  - pscp.exe
  - copy.exe
  - robocopy.exe
  - certutil.exe
  - vssadmin.exe
  - powershell.exe
  - wevtutil.exe
  - psexec.exe
  - bcedit.exe
  - wbadmin.exe
  - icacls.exe
  - diskpart.exe

-------------------

### Possible causes of false positives

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://car.mitre.org/wiki/CAR-2013-04-002

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
