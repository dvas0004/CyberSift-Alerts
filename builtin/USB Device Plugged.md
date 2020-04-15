# USB Device Plugged
### Description

Detects plugged USB devices.

-------------------
### Severity

- Low

-------------------

### Detailed Information

Detects USB devices plugged in via the following events:

  - 2003  # Loading drivers
  - 2100  # Pnp or power management
  - 2102  # Pnp or power management

-------------------

### Possible causes of false positives

- Legitimate administrative activity

-------------------
### References

- https://df-stream.com/2014/01/the-windows-7-event-log-and-usb-device/
- https://www.techrepublic.com/article/how-to-track-down-usb-flash-drive-usage-in-windows-10s-event-viewer/

-------------------
### Supported Log Sources

- windows driver-framework

-------------------
