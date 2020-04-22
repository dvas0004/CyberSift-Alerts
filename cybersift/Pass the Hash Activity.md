# Pass the Hash Activity
### Description

Detects the attack technique pass the hash which is used to move laterally inside the network

-------------------
### Severity

Medium

-------------------

### Detailed Information

Events:
  - 4624 An account was successfully logged on.
    - Security ID: NULL 
    - Logon Type: 3 (Network) AND Logon Process Name: NtLmSsp
    - Logon Type: 9 (Process run using RunAs command to run as another user using the /netonly option) 
      AND Logon Process Name: seclogo
    
-------------------
### Possible causes of false positives

- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)

-------------------

### References

- https://github.com/iadgov/Event-Forwarding-Guidance/tree/master/Events
- https://blog.binarydefense.com/reliably-detecting-pass-the-hash-through-event-log-analysis
- https://blog.stealthbits.com/how-to-detect-pass-the-hash-attacks/

-------------------
### Supported Log Sources

- windows security

-------------------
