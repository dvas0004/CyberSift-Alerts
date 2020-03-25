# LSASS Access Detected via Attack Surface Reduction
### Description

Detects Access to LSASS Process

-------------------
### Severity

High

-------------------
### Detailed Information

Definitions
  - 'Requirements:Enabled Block credential stealing from the Windows local security authority subsystem (lsass.exe) from Attack Surface Reduction (GUID: 9e6c4e1f-7d60-472f-ba1a-a39ef669e4b2)'


-------------------
### Possible causes of false positives

- Google Chrome GoogleUpdate.exe
- Some Taskmgr.exe related activity

-------------------
### References

- https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-defender-exploit-guard/attack-surface-reduction-exploit-guard?WT.mc_id=twitter

-------------------
### Supported Log Sources

-windows defender

-------------------
