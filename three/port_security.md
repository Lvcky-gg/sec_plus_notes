# Port Security

- control and protect

## Broadcasts

- send information to everyone at once
- limited scope
- routing updates, ARP request can add up quickly
- malicious software or a bad NIC
- not used in IPv6

## Broadcast storm control

- the switch can control broadcasts
- can often be used to control multicast and unknown unicast traffic
- manage by specific values or by percentage

## Loop protection

- connect two switches together
- this is an easy way to bring down a network
- IEEE Standard 802.1D to prevent loops in bridged

## BPDU Guard

- spanning tree takes time to determine if a switch port should span forward frames
- Bridge Protocol Data Unit
- if seen on a PortFast configured interface, shut down the interface

## DHCP snooping

- IP tracking on layer 2 device
- switch watches for DHCP conversations
- filters invalid DHCP information

## MAC filtering

- Media access control: the hardware address
- limit access through the physical hardware address
- easy to find working MAC address through wireless LAN analysis
