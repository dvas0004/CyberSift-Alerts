# Kerberos Manipulation
### Description

This method triggers on rare Kerberos Failure Codes caused by manipulations of Kerberos messages.

-------------------
### Severity

- High

-------------------

### Detailed Information

Fires on the following Windows Log Event IDs :
  - 675
  - 4768
  - 4769
  - 4771

With the following Kerberos Failure Codes:
  - '0x9'
  - '0xA'
  - '0xB'
  - '0xF'
  - '0x10'
  - '0x11'
  - '0x13'
  - '0x14'
  - '0x1A'
  - '0x1F'
  - '0x21'
  - '0x22'
  - '0x23'
  - '0x24'
  - '0x26'
  - '0x27'
  - '0x28'
  - '0x29'
  - '0x2C'
  - '0x2D'
  - '0x2E'
  - '0x2F'
  - '0x31'
  - '0x32'
  - '0x3E'
  - '0x3F'
  - '0x40'
  - '0x41'
  - '0x43'
  - '0x44'

-------------------

### Possible causes of false positives

- Faulty legacy applications

-------------------
### References

- https://www.ultimatewindowssecurity.com/securitylog/book/page.aspx?spid=chapter4

-------------------
### Supported Log Sources

- Windows Security

-------------------
