# Backup Catalog Deleted
### Description

Detects backup catalog deletions.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

"Wbadmin delete catalog", deletes the backup catalog that is stored on the local computer. Use this command when the backup catalog has been corrupted and you cannot restore it using wbadmin restore catalog.

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://technet.microsoft.com/en-us/library/cc742154(v=ws.11).aspx
- https://www.hybrid-analysis.com/sample/ed01ebfbc9eb5bbea545af4d01bf5f1071661840480439c6e5babe8e080e41aa?environmentId=100

-------------------
### Supported Log Sources

- windows application

-------------------
