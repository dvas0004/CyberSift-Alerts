# Enabled User Right in AD to Control User Objects
### Description

Detects scenario where if a user is assigned the SeEnableDelegationPrivilege right in Active Directory it would allow control of other AD user objects.

-------------------
### Severity

High

-------------------
### Detailed Information

SeEnableDelegationPrivilege allows an account to delegate access to containers and subtrees to other users and groups.
In an Active Directory environment, only the domain controller should have this privilege.
If we control an object that has SeEnableDelegationPrivilege in the domain, AND said object has GenericAll/GenericWrite rights over any other user object in the domain, we can compromise the domain at will, indefinitely.

-------------------
### Possible causes of false positives

Unknown

-------------------
### References

- https://www.harmj0y.net/blog/activedirectory/the-most-dangerous-user-right-you-probably-have-never-heard-of/

-------------------
### Supported Log Sources

- windows security

-------------------
