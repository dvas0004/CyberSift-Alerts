# Microsoft Binary Github Communication
### Description

Detects an executable in the Windows folder accessing github.com

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon event "Network connection" (ID 3) where the DestinationHostname field fits:
  - '*.github.com'
  - '*.githubusercontent.com'
<br>AND<br>
the Image field fits 'C:\Windows\\*' (ie: the process executable making the connection is inside the Windows directory)



-------------------

### Possible causes of false positives

- 'Unknown'
- '@subTee in your network'

-------------------
### References

- https://twitter.com/M_haggis/status/900741347035889665
- https://twitter.com/M_haggis/status/1032799638213066752

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
