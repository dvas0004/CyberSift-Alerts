# Unusual Connection
### Description

Checks for unusual connections made by network nodes, both locally and externally.

-------------------
### Severity

Low

-------------------
### Detailed Information

Checks for unusual connections on two levels:

Globally:
A server makes a connection to an unusual port which no other servers in your network make, or, 
the server is connecting to the internet with ports/number of connections/avg bytes transferred in a different way than other
servers in your network do.

Locally:
The same metrics are used except the server's behaviour is compared to its own behaviour,
rather than that of other nodes in the network.

-------------------
### Possible causes of false positives

- Legitimate Connections

-------------------
### References

- None

-------------------
### Supported Log Sources

- firewall
- router
- switch

-------------------
