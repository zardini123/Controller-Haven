# Controller Haven

## WiiBalanceWalker

v0.5 https://github.com/lshachar/WiiBalanceWalker

## Protocols

### Dolphin's UDPWii protocol

https://github.com/EZForever/UDPWiiHook/wiki/Protocol

Things using UDPWii:
- https://github.com/EZForever/UDPMote

### DSUS (DSU/Cemuhook) protocol

https://github.com/v1993/cemuhook-protocol

DS4Windows maintainer Ryochan7 documented some part of the protocol [here](https://github.com/Ryochan7/DS4Windows/wiki/UDP-Server-Output-Packet-Information) ([issue from DS4Windows this is referenced in](https://github.com/Ryochan7/DS4Windows/issues/437)).

Things using DSUS Server (controller provider):
- DS4Windows ([C# class](https://github.com/Ryochan7/DS4Windows/blob/0eb21ef17aaf50876b2b6dbddb68b18f70c18772/DS4Windows/DS4Control/UdpServer.cs))

Things using DSUS Client (controller reciever):
- Cemu
