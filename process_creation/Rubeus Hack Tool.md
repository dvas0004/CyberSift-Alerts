# Rubeus Hack Tool
### Description

Detects command line parameters used by Rubeus hack tool

-------------------
### Severity

- Critical

-------------------

### Detailed Information
Triggers on commands fitting one of the following wildcard patterns:
  - '* asreproast *'
  - '* dump /service:krbtgt *'
  - '* kerberoast *'
  - '* createnetonly /program:*'
  - '* ptt /ticket:*'
  - '* /impersonateuser:*'
  - '* renew /ticket:*'
  - '* asktgt /user:*'
  - '* harvest /interval:*'

-------------------

### Possible causes of false positives

- Unlikely

-------------------
### References

- https://www.harmj0y.net/blog/redteaming/from-kekeo-to-rubeus/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
