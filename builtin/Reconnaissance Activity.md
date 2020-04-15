# Reconnaissance Activity
### Description

Detects activity as "net user administrator /domain" and "net group domain admins /domain"

-------------------
### Severity

- High

-------------------
### Detailed Information

- 4661 Opened a SAM Object

Fires when somebody opens a SAM_USER or SAM_GROUP object with File Read and Write Access (Access Mask 0x21).

-------------------
### Possible causes of false positives

  - Administrator activity
  - Penetration tests

-------------------
### References

  - https://findingbad.blogspot.de/2017/01/hunting-what-does-it-look-like.html

-------------------
### Supported Log Sources

- windows security

-------------------
