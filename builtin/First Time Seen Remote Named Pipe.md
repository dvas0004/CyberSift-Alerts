# First Time Seen Remote Named Pipe
### Description

Detects never before seen named pipes.

-------------------
### Severity

- High

-------------------

### Detailed Information

This detection excludes known named pipes accessible remotely and notifies only on newly observed ones. 
May help to detect lateral movement and remote execution using named pipes.

-------------------

### Possible causes of false positives

- update the excluded named pipe to filter out any newly observed legit named pipe

-------------------
### References

- https://twitter.com/menasec1/status/1104489274387451904

-------------------
### Supported Log Sources

- Windows Security

-------------------
