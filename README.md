# NETBW - bash "iftop"

netbw displays the current network traffic.

# Usage

```
$ . ./netbw
$ netbw enp3s0f1
enp3s0f1: tx: 66bytes - rx: 398bytes
enp3s0f1: tx: [___________] - rx: [___________] 

```
display is refreshed every seconds and the 2 bars are showing the percentage of interface speed used (defaults to 1G if speed is not applicable for the interface, like with bridges).
