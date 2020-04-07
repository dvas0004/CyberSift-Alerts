# Addition of SID History to Active Directory Object
### Description

An attacker can use the SID history attribute to gain additional privileges.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

SID History is an attribute that supports migration scenarios. Every user account has an associated Security IDentifier (SID) which is used to track the security principal and the access the account has when connecting to resources. SID History enables access for another account to effectively be cloned to another. This is extremely useful to ensure users retain access when moved (migrated) from one domain to another. Since the user’s SID changes when the new account is created, the old SID needs to map to the new one. When a user in Domain A is migrated to Domain B, a new user account is created in DomainB and DomainA user’s SID is added to DomainB’s user account’s SID History attribute. This ensures that DomainB user can still access resources in DomainA.

Mimikatz enables SID History injection to any user account (requires Domain Admin or equivalent rights). In this scenario, the attacker creates the user account “bobafett” and adds the default administrator account for the domain, “ADSAdministrator” (RID 500), to the account’s SID History attribute.

Detection of successful modification or failed attempt to modify the SIDHistory attribute is possible with the following logging:

Configure sub-category auditing under Account Management,  “Audit User Account Management” (success) on Domain Controllers for the following event ids:

4765: SID History was added to an account.
4766: An attempt to add SID History to an account failed.

-------------------

### Possible causes of false positives

- Migration of an account into a new domain

-------------------
### References

- https://adsecurity.org/?p=1772

-------------------
### Supported Log Sources

- windows security

-------------------
