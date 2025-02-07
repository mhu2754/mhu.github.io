---
layout: default
---

## RCOPY

'rcopy' is a linux command that allows a user to copy a file from one location/ports to another through sockets. In my own implementation, I utilized UDP sockets to transfer data, along with a sliding/circular window buffer to keep track of data, Ready Receive (RR), and Selective Reject (SREJ) packets. 
