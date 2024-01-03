# Wireless Cryptography

## Securing a wireless network

- wireless network can contain confidential information
- authenticate users before granting access
- verify integrity of all communication

## Wireless Encryption

- all wireless computers are radio transmitters and recievers
- encrypt data
- only people with the right key can listen and transmitters
  - WPA2 and WPA3

## WPA2 and CCMP

- wifi protected access 2
- CCMP block cipher mode
  - counter mode with cipher block chaining
  - message authentication code protocol
  - counter/cbc-mac protocol
- CCMP security services: data confidentiality with AES and message integrity check ewith cbc-mac

## WPA3 and GCMP

- wifi protected access 3
- GCMP block cipher mode
  - galois counter mode
  - stronger than WPA2
- data confidentiality with AES and message integrity check with MIC

## WPA2 PSK problem

- has a psk brute force protection: listen to 4 way handshake and capture hash
- attackers can take the hash and brute force the pre shared key
- it is relatively easy as tech improves

## SAE

- WPA3 changes the process to include mutual authentication and a shared session key
- SImaltanously Authentication of Equals(SAE)
- a diffie hellman derived key exchange
- everyone uses a different session key
- IEEE standard
