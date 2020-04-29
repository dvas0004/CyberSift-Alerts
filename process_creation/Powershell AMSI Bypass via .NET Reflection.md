# Powershell AMSI Bypass via .NET Reflection
### Description

Detects Request to amsiInitFailed that can be used to disable AMSI Scanning

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on command line intstructions containing 'System.Management.Automation.AmsiUtils' and 'amsiInitFailed'

-------------------

### Possible causes of false positives

- Potential Admin Activity

-------------------
### References

- https://twitter.com/mattifestation/status/735261176745988096
- https://www.hybrid-analysis.com/sample/0ced17419e01663a0cd836c9c2eb925e3031ffb5b18ccf35f4dea5d586d0203e?environmentId=120

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
