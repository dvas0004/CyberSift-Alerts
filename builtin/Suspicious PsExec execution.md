# Suspicious PsExec execution
### Description

Detects execution of psexec or paexec with renamed service name,
this rule helps to filter out the noise if psexec is used for legit purposes or if attacker uses a different psexec client other than sysinternal one.

-------------------
### Severity

- High

-------------------

### Detailed Information

Events:
  - 5145 A network share object was checked to see whether client can be granted desired access
  
Triggers on:
  - Share name fitting pattern '\\*\IPC$'
  - Target Name fitting: '*-stdin' or '*-stdout' or '*-stderr'
or:
  - Share name fitting pattern '\\*\IPC$'
  - Target name fitting: 'PSEXESVC*'
  
-------------------

### Possible causes of false positives

  - None observed so far.
  - Unknown

-------------------
### References

- https://blog.menasec.net/2019/02/threat-hunting-3-detecting-psexec.html

-------------------
### Supported Log Sources

- windows security

-------------------
