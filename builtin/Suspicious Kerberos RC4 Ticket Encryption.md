# Suspicious Kerberos RC4 Ticket Encryption
### Description

Detects service ticket requests using RC4 encryption type.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

Events:
  - 4769 Kerberos Ticket Request
 
 Triggers on Kerberos ticket request with ticket options 0x40810000 (Forwardable, Renewable, Canonicalize) and encryption type
 0x17 (RC4-HMAC)

-------------------

### Possible causes of false positives

- Service accounts used on legacy systems (e.g. NetApp)
- Windows Domains with DFL 2003 and legacy systems

-------------------
### References

- https://adsecurity.org/?p=3458
- https://www.trimarcsecurity.com/single-post/TrimarcResearch/Detecting-Kerberoasting-Activity

-------------------
### Supported Log Sources

- windows security

-------------------
