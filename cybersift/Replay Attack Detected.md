# Replay Attack Detected
### Description

A replay attack was detected. May be a harmless false positive due to misconfiguration error.

-------------------
### Severity

High

-------------------
### Detailed Information

Events:
  - 4649 Replay Attack detected.

Event generates on domain controllers when KRB_AP_ERR_REPEAT Kerberos response was sent to the client.

-------------------

### Possible causes of false positives

- Misconfigured network device between the client and server that could send the same packet(s) repeatedly.

-------------------

### References

- https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/plan/appendix-l--events-to-monitor 
- https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/event-4649#security-monitoring-recommendations

-------------------
### Supported Log Sources

- windows security

-------------------
