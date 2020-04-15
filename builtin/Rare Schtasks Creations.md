# Rare Schtasks Creations
### Description

Detects rare scheduled tasks creations that only appear a few times per time frame and could reveal password dumpers, backdoor installs or other types of malicious code.

-------------------
### Severity

- Low

-------------------

### Detailed Information

Events:
  - 4698 Scheduled Task Creation

timeframe: 7d

condition: selection | count() by TaskName < 5 
 
Triggers on a rare scheduled task being scheduled more than 5 times in a 7 Day timeframe.

-------------------

### Possible causes of false positives

- Software installation
- Software updates

-------------------

### Supported Log Sources

- windows security

-------------------
