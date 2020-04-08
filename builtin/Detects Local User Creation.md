# Detects Local User Creation
### Description

Detects local user creation on windows servers, which shouldn't happen in an Active Directory environment.
Apply this Sigma Use Case on your windows server logs and not on your DC logs.

-------------------
### Severity

- Low

-------------------
### Detailed Information

By monitoring the Event Log 4720 on non domain controller, we are able to detect user creation.
In An Active Directory environment, only the domain controller should be associated with these events.
This rule monitors for events with ID 4720 indicating the creation of a local user account.

-------------------
### Possible causes of false positives

- Domain Controller Logs
- Local accounts managed by privileged account management tools

-------------------
### References

- https://patrick-bareiss.com/detecting-local-user-creation-in-ad-with-sigma/

-------------------
### Supported Log Sources

- windows security

-------------------
