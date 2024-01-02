# Virtual Private Networks

- encrypted private data traversing a public Networks
- concentrator
  - encryption/decryption access device
  - integrated into firewall
- many deployment options
  - specialized crypto hardware
  - software based
- used with client software

## SSL VPN(Secure Socket layer VPN)

- uses common SSL/TLS protocol
- no big VPN clients
- authenticate users
- can be run from a browser

## Remote access VPN

- on demand access from a remote device
- some software can be configured as always on

## L2TP

- layer 2 tunneling, connecting sites over layer 3 as if they were at layer 2

- commonly used with IPSEC

## IPSec(Internet Protocol Security

- security for os layer 3
- confidentiality and integrity/anti-replay
- very standardized
- two core modules
  - authentication header(AH)
  - encapsulation security payload(ESP)

## AH authentication header

- data integrity
- origin authentication
- keyed-hash mechanism
- no confidentiality

## ESP encapsulating security payload

- data confidentiality
- limited traffic flow
- data integrity
- anti-replay

## AH and ESP- combine the two
