# Whoami Execution
### Description

Detects the execution of whoami, which is often used by attackers after exloitation / privilege escalation but rarely used by administrators.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on running of the command 'whoami' from windows CMD or Powershell.

-------------------

### Possible causes of false positives

- Admin activity
- Scripts and administrative tools used in the monitored environment

-------------------
### References

- https://twitter.com/haroonmeer/status/939099379834658817
- https://twitter.com/c_APT_ure/status/939475433711722497

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
