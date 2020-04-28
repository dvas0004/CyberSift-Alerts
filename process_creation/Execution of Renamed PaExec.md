# Execution of Renamed PaExec 
### Description

Detects execution of renamed paexec via imphash and executable product string.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on Executable having one of the following md5 hashes:
  - 11D40A7B7876288F919AB819CC2D9802
  - 6444f8a34e99b8f7d9647de66aabe516
  - dfd6aa3f7b2b1035b76b718f1ddc689f
  - 1a6cca4d5460b1710a12dea39e4a592c

-------------------

### Possible causes of false positives

- Unknown imphashes

-------------------
### References

- sha256=01a461ad68d11b5b5096f45eb54df9ba62c5af413fa9eb544eacb598373a26bc 
- https://summit.fireeye.com/content/dam/fireeye-www/summit/cds-2018/presentations/cds18-technical-s05-att&cking-fin7.pdf

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
