# Reconnaissance Activity with Net Command
### Description

Detects a set of commands often used in recon stages by different attack groups.

-------------------
### Severity

Medium

-------------------

### Detailed Information
Triggers on running of 5 or more of the following commands:

  - tasklist
  - net time
  - systeminfo
  - whoami
  - nbtstat
  - net start
  - '*\net1 start'
  - qprocess
  - nslookup
  - hostname.exe
  - '*\net1 user /domain'
  - '*\net1 group /domain'
  - '*\net1 group "domain admins" /domain'
  - '*\net1 group "Exchange Trusted Subsystem" /domain'
  - '*\net1 accounts /domain'
  - '*\net1 user net localgroup administrators'
  - netstat -an

-------------------

### Possible causes of false positives

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://twitter.com/haroonmeer/status/939099379834658817
- https://twitter.com/c_APT_ure/status/939475433711722497
- https://www.fireeye.com/blog/threat-research/2016/05/targeted_attacksaga.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
