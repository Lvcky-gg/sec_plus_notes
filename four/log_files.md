# Log Files

## Network Log Files

- switches, routers, access points, VPN concentrators
- network changes

## system Log Files

- OS information
- can also include security events

## Application log Files

- specific to the application
- windows - event viewer / application log
- linux / macOS -/var/log
- parse the log details to the SIEM

## Security log files

- detailed security related information
  - blocked and allowed traffic flows
  - exploit attempts
  - blocked URL categories
  - DNS sinkhole
- security devices
  - IPS, firewall, proxy
- critical security information

## Web log files

- web server access
- access errors
- exploit attempts
- server activity

## DNS log files

- view lookup requests
- IP address of the request
- identify queries to known bad URLs
- block and modify known bad requests

## Authentication log files

- know who is logged in
- identify multiple failures
- correlate with other events

## Dump files

- store all contents of memory into a diagnostic file
- easy to create from the windows task manager
- some applications have their own dump file process

## VoIP and Call Manager Logs

- view inbound and outbound call info
- security information
- SIP traffic logs
  - Session Initiation protocol
  - call setup, management and teardown
