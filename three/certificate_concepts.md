# Certificate Concepts

## Online and Offline CAs

- a compromised certificate authority is bad
- distribute the load and then take CA offline

## OCSP stapling

- online certificate status protocols provive scaling for OCSP checks
- CA is responsible for responding to all client OSCP requests
- have cert holder verify their own status
- OCSP status is stapled into ssl/tls handshake

## Pinning

- you are communicating over TLS/SSL server and need to know it is legit
- pin the expected cert or public key to an app
- if expected cert doesn't match, app can decide what to do

## PKI trust relationships

- single CA, everyone recieves certs from one authority
- hierarchical, single CA issues certs to intermediate CA
- mesh, cross certifying CAs
- web of trust, alternate to traditional PKI
- mutual authentication, server authenticates the client and client authenticates server

## Key Escrow

- someone holds your decryption keys
- this can be a legitimate arrangement

## Certificate Chaining

- chain of trust
- starts with ssl cert and ends with root cert
- any cert between the two is included
- web server needs to be configured with proper chain
