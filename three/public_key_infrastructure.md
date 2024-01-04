# Public Key Infrastructure

- PKI
- policies, proceedures, hardware, software, people
- big endeavor
- also refers to binding public keys to people or devices

## Key management lifecycle

- key generation
- cert generation
- distribution
- storage
- revocation
- expiration

## Digital Certificates

- a public key Certificates
- a digital signature adds trust
- certificate creation can be built into the OS

## Commercial Certificate Authorities

- built by browser
- purchase your web site certificate
- create a key pair
- may provide different levels of trust

## Private certificate Authorities

- you are your own CA
- needed for medium-large organizations
- implement as part of your overall computing strategy

## PKI trust relationships

- single CA
- hierarchical

## Registration Authority(RA)

- the entity requesting the certificate needs to be verified by the RA
- approval or rejection
- also responsible for revokation
- manages renewals and re-key requests

## Important certificate attributes

- common name(CN)
- subject alternate name
- expiration

## Key revocation

- certificate revocation list (CRL)
- many reasons

## getting revocation to the browser

- OSCP(Online Certificate Status Protocol)
- Messages usually sent to an OCSP responder via HTTP
- not all browsers support OSCP
