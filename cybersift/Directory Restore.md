# Directory Services Restore Mode
###  An attempt was made to set the Directory Services Restore Mode.
-------------------
### Severity

High
-------------------
### Possible causes of false positives

- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)
-------------------
### References

 - https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/plan/appendix-l--events-to-monitor 
 - https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/event-4794#security-monitoring-recommendations
-------------------
### Supported Log Sources

- windows security
-------------------
