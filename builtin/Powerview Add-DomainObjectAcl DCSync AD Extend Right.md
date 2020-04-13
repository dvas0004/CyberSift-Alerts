# Powerview Add-DomainObjectAcl DCSync AD Extend Right
### Description

Backdooring domain object to grant the rights associated with DCSync to a regular user or machine account using Powerview\Add-DomainObjectAcl DCSync Extended Right cmdlet, 
will allow to re-obtain the pwd hashes of any user/computer

-------------------
### Severity

Critical

-------------------
### Detailed Information

Events:
  - 5136 (Directory Service Object Was Modified)

LDAP Display Name: 
  nTSecurityDescriptor
  
Values (nTSecurityDescriptor:
  - '*1131f6ad-9c07-11d1-f79f-00c04fc2dcd2*'
  - '*1131f6aa-9c07-11d1-f79f-00c04fc2dcd2*'

  
-------------------
### Possible causes of false positives

- New Domain Controller computer account, check user SIDs witin the value attribute of event 5136 and verify if it's a regular user or DC computer account.

-------------------

### References

- https://twitter.com/menasec1/status/1111556090137903104
- https://www.specterops.io/assets/resources/an_ace_up_the_sleeve.pdf

-------------------
### Supported Log Sources

- windows security

-------------------
