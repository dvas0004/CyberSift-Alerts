# Windows Logon Events Context Addition
### Description

Default windows logon events (ID 4624) are updated with several CyberSift-specific fields during context addition to make analysis easier.

-------------------
### Severity

- Info

-------------------
### Detailed Information

![summary_diagram](https://../../../img/WindowsLogonEventContextAddition.jpg)

#### Field description for Source (where logon request came from (a.k.a “Workstation”)

- Hostname 
  
**winlog.event_data.WorkstationName**

(not always available, though CyberSift performs its own lookup and inserts this if the original is not available)

- Usual Users logged into this PC/Server

**winlog.event_data.WorkstationUsers** 


#### Field description for Destination (where User would like to logon to)

- Usual Users logged into this PC/Server
  
**winlog.SourceUsers**


- Logon Type Friendly Name
  
**winlog.event_data.LogonTypeText**



-------------------
### Possible causes of false positives

- Windows logging does not always include the "Source" IP address or name so in some corner cases the context addition fields would be unavailable

-------------------
### References

- [Event Description](https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/event.aspx?eventID=4624)
- [List of login types](https://www.manageengine.com/products/active-directory-audit/kb/windows-security-log-event-id-4624.html)


-------------------
### Supported Log Sources

- Windows Security Audit logs (Event ID 4624)
-------------------
