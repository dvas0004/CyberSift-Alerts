# SquiblyTwo
### Description

Detects WMI SquiblyTwo Attack with possible renamed WMI by looking for imphash.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

Triggers on wmic.exe being run with one of the following parameters:
  - format:\"http*
  - /format:'http
  - /format:http*

To account for the case where wmic.exe has been renamed, the rule will also trigger if the hash of the imports listed in the PE header (the "imphash") of the executable matches one of the following hashes (in addition to being run with one of the above parameters):

  - 1B1A3F43BF37B5BFE60751F2EE2F326E
  - 37777A96245A3C74EB217308F3546F4C
  - 9D87C9D67CE724033C0B40CC4CA1B206

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://subt0x11.blogspot.ch/2018/04/wmicexe-whitelisting-bypass-hacking.html
- https://twitter.com/mattifestation/status/986280382042595328

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
