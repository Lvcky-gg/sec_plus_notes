# Certificates

## Web Server SSL Certificates

- domain validation Certificates: owner of cert has some domain control
- extended validation certificate(EV) : additional checks validate owner's identity
- subject alternate name(SAN): extension to x.509 cert, allows cert on many domains
- wildcard domain : certs are based on name of server, applies to all server names in domain

## Code Signing Certificates

- developers can add a level of trust, they can sign apps
- user's os will examine signature
- is it trusted?

## Root Certificates

- public key certificate that identifies the root CA(certificate authority)
- it issues other certs
- very important cert, keep it safe

## Self signed certs

- internal certs don't need to be signed by a public CA
- build your own CA
- install the CA certificate/trusted chain on all devices

## Machine and Computer Certs

- you have to manage many devices
- put a cert on a device you signed to establish trust
- other business processes will rely on cert

## Email certs

- use cryptography in an email platform
- encrypt emails with recipient public key
- recieve emails and decrypt with your private key
- digital signatures use your private key to sign an email and provide non-repudiation

## User Certs

- associate a cert with a user
- use as additional authentication factor
- integrate into smart cards
