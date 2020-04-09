# File Delete Volume Anomaly
### Description

Fires when a user deletes an unusually large number of files.

-------------------
### Severity

- Medium

-------------------
### Detailed Information

- Every hour, we aggregate windows event logs to search for file access events over the past one hour.
- Filter the events to consider only those whose "AccessMask" is set to either "0x10000" or "0x40". 
  These hex numbers are what access levels the user actually used (not just asked for), in particular:
    - We record the number of events generated, grouped by the user who initiated that event. 
    - Over time, we build a history of how many events each user typically generates
    - If in this particular hour, the number of events is more than 3x the average (accounting for variation as well), we mark all the delete events in that hour as an anomaly.

-------------------
### Possible causes of false positives

- Legitimate bulk deletion operations.

-------------------
### References

- https://docs.microsoft.com/en-us/windows/win32/secauthz/access-rights-and-access-masks

-------------------
### Supported Log Sources

- windows logs

-------------------
