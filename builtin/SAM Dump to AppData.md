# SAM Dump to AppData
### Description

Detects suspicious SAM dump activity as cause by QuarksPwDump and other password dumpers.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on event logs containing keywords fitting the following pattern: '*\AppData\Local\Temp\SAM-*.dmp *'

-------------------

### Possible causes of false positives

- Penetration testing

-------------------
### References

- None

-------------------
### Supported Log Sources

- windows system

-------------------
