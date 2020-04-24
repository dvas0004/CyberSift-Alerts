# NTFS Alternate Data Stream
### Description

Detects writing data into NTFS alternate data streams from powershell. Needs Script Block Logging.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on Powershell keywords:

  - "set-content"
  - "-stream"

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- http://www.powertheshell.com/ntfsstreams/

-------------------
### Supported Log Sources

- Windows Powershell

-------------------
