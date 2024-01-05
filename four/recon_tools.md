# Recon Tools

## Traceroute

- determine the route a packet takes to a destination, map the entire path

## tracert

- takes advantage of ICMP time to live exceeded error message
- not all devices will reply with ICMP time exceeded messages

## nslookup and dig

- lookup information from DNS servers

## nslookup

- both windows and posix based: lookup names and IP addresses

## dig(Domain Information Groper)

- more advanced domain information
- probably your first choice

## IPconfig and IFconfig

- most of your troubleshooting starts with your IP address
- determine TCP/IP and network adapter information

## ipconfig

- windows TCP/IP config

## ifconfig

- linux interface configuration

## NMAP

- network mapper
- port scans
- operating system scan
- service scan
- additional scripts: Nmap Scripting Engine(NSE)

## ping

- test reachability
- one of your primary troubleshooting tools

## pathping

- combine ping and traceroute
- first phase runs a traceroute
- second phase

## hping

- TCP/IP packet assembler/analyzer
- ping a device
- send crafted frames to modify IP, TCP, UDP, and ICMP
- a powerful tool

## netstat

- network statistics

## netstat -a

- show all active connections

## netstat -b

- show binaries

## netstat -n

- do not resolve names

## netcat

- read or write to the network: open a port and send or receive some traffic
- many different functions
- become a backdoor

## IP scanners

- search a network for IP addresses
- many different techniques
  - ARP
  - ICMP
  - TCP ACK
  - ICMP
- a response means more recon can be done

## Address Resolution protocol

- determine a MAC address based on an IP address

- arp -a

  - view local ARP table

- route

  - view the device's routing table
  - windows: route print
  - linux and macOS: netstat -r

- curl

  - client URL
  - grab raw data

## theHarvester

- gather OSINT
  - OSINT
- scrape information from Google or Bing
- list of people LinkedIn
- find PGP keys by email domain
- DNS brute force

## Sn1per

- combine many recon tools into a single framework
- both non-intrusive and very intrusive scanning options
- another tool that can cause problems

## scanless

- run port scans from a different host
  - port scan proxy
- many different services

## dnsenum

- enumerate DNS information
- view host information from DNS servers
- find host names in Google

## Nessus

- industry leader in vulnerability scanning
- identify known vulnerabilities
- extensive reporting

## Cuckoo

- a sandbox for malware
- a virtualized environment
- track and trace api calls, network traffic, memory analysis
