# Suspicious Outbound RDP Connections 
### Description

Detects Non-Standard Tools Connecting to TCP port 3389 indicating possible lateral movement.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon Event 'Network Connection' (ID 3) where DestinationPort equals 3389 and connecting process (Image attribute) is one of:
  - '*\mstsc.exe'
  - '*\RTSApp.exe'
  - '*\RTS2App.exe'
  - '*\RDCMan.exe'
  - '*\ws_TunnelService.exe'
  - '*\RSSensor.exe'
  - '*\RemoteDesktopManagerFree.exe'
  - '*\RemoteDesktopManager.exe'
  - '*\RemoteDesktopManager64.exe'
  - '*\mRemoteNG.exe'
  - '*\mRemote.exe'
  - '*\Terminals.exe'
  - '*\spiceworks-finder.exe'
  - '*\FSDiscovery.exe'
  - '*\FSAssessment.exe'
  - '*\MobaRTE.exe'
  - '*\chrome.exe'
-------------------

### Possible causes of false positives

- Other Remote Desktop RDP tools

-------------------
### References

- https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2019-0708

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
