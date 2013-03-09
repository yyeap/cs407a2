CS 407 Assignment 2 Wireless Network Test
=========================================

Ethernet
--------
Machine: mumble-16.cs.wisc.edu
###iperf
```iperf -c iperf.wsicnet.net -i0.1```

###ping
```ping iperf.wiscnet.net -c 100```

Wifi
----
OS: Windows 7
WLAN Network: COMPSCI-OPEN
###iperf
```bin/iperf.exe -c iperf.wiscnet.net -P 1 -i 1 -p 5001 -f k -t 10```

###ping
```ping -n 100 -l 64 iperf.wiscnet.net```

