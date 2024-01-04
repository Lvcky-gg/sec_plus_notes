# PAP password authentication protocol

- basic authentication method
- PAP is in the clear
  - weak authentication
  - non encrypted password exchange
  - didnt require encryption on analog dialup

## CHAP

- challenge handshake authentication protocol: encrypted challenge sent over a network
- three way handshake
  - after link is established, server sends a challenge
  - client responds with a password hash calculated
  - server compares recieved hash calculated from the challenge and password
- challenge response continues

## MS-CHAP

- microsoft implementation of CHAP
- commonly used by microsoft
- point to point tunneling protocol(pptp)
- v2 is more recent
- Security issues related to DES
  - easy to brute force the 256 possible keys
  - don't use ms-chap
  - consider l2tp, ipsec, 802.1x
