# Abnormal Login Privileges
### Description

A user has logged into SWIFT using an unusual profile

-------------------
### Severity

- Medium

-------------------
### Detailed Information

This alert is triggered when a SWIFT user logs into the system using a never before obeserved "Operator Profile". Once seen, the user and operator profile are "remembered" for a set period of time before being scrubbed from memory. 

Since the user is logging in with a new profile, this could be a sign that their account credentials have been compromised and an attacker is attempting to login using a profile that gives them more freedom to carry out attacks.

An analyst should check if this user has every used the profile in question before in the past (to ensure this is not a false positive due to too short a "Remember" timer), and should also check if any other users have been using this profile (i.e. "is this a common occurance in my organisation?").

-------------------
### Possible causes of false positives

- ML model is still in it's initial "learning" phase, when it would mark any incoming data as being novel and therefore "abnormal"
- ML model "Remember" timer is too short

-------------------
### References

- [MITRE ATT&CK: Identify personnel with an authority/privilege](https://attack.mitre.org/techniques/T1271/)
- [MITRE ATT&CK: Privilege Escalation](https://attack.mitre.org/tactics/TA0004/)

-------------------
### Supported Log Sources

- Windows: Application

-------------------
