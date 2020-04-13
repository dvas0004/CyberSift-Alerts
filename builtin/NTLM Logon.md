# NTLM Logon
### Description

Detects logons using NTLM, which could be caused by a legacy source or attackers.

-------------------
### Severity

- Low

-------------------

### Detailed Information

Active directory logons should be through Kerberos on modern systems. NTLM authentication could be a sign of a downgrade attack.

-------------------

### Possible causes of false positives

- Legacy hosts

-------------------
### References

- https://twitter.com/JohnLaTwC/status/1004895028995477505
- https://goo.gl/PsqrhT
    
-------------------
### Supported Log Sources

- Windows NTLM

-------------------
