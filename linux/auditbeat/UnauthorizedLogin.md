# Unauthorized Login Detected
### Description

This alert is generated when Auditbeat integration with FreeIPA is configured via NiFi. An unauthorized user is one who is a valid user with valid credentials, however they are not allowed access to a given host (controlled via FreeIPA hostgroups)

-------------------
### Severity

- High

-------------------
### Detailed Information

FreeIPA HBA allows you to define "hostgroups", which contain lists of authorized users who are allowed to login to servers which are included in a hostgroup. Any user not in a server's allowed users is denied login. Auditbeat generates an event when this happens, but an additional check is performed by CyberSift via the FreeIPA API to see if the denied login was caused by the user being unauthorized. If so, this alert is generated. An administrator can whitelist users, sources and destinations by doing the following:

- SSH into the cybersift server and issue the following commands:

```bash
redis-cli
> sadd authorized-users-sourceAddress-destinationAddress username
> srem authorized-users-sourceAddress-destinationAddress username
```

`sadd` will add a user while `srem` will remove a user. For example:

```
> sadd authorized-users-192.168.2.1-10.20.1.1 david
```
The above command will allow user "david" to login **from the client IP** 192.168.2.1 **to the server IP** 10.20.1.1

-------------------
### Possible causes of false positives

- Local accounts used which are not listed in FreeIPA

-------------------
### References

- [MITRE "Valid Accounts" (T1078)](https://attack.mitre.org/techniques/T1078/)
- [FreeIPA HBAC](https://www.freeipa.org/page/Howto/HBAC_and_allow_all)

-------------------
### Supported Log Sources

- auditbeat

-------------------
