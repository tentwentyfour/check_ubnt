# check_ubnt
Nagios check for Ubiquiti AirOS devices via Telnet

Plugin is usable, but not complete. Metrics for test usage are
* ccq
* rssi
* rxrate
* txrate
* signal (-dBm)
* noise figure (dBm)

Sample output:
```
UBIQUITI OK - ccq is 991
| ccq=991 noisef=100 rssi=41 rxrate=36.111 signal=55 txrate=32.5

```
