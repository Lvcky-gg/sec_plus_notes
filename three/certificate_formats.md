# Certificate Formats

## Certificate File Formats

- x.509 digital Certificate: structure is standardized
- many Formats

## DER(Distinguished Encoding Rules)

- format designed to transfer syntax for data structures
- binary format
- not common format

## PEM(Privacy enhanced mail)

- very common
- ASCII format

## PKCS #12

- public key cryptography standards 12
- container storage format for many certificates
- extended for .pfx format

## CER(Certificate)

- primarily a windows x.509 file extension
- usually contains a public key
- common windows cert .cer

## PKCS #7

- public key cryptography standards #7
- stored in ASCII format
- contains certs and chain reciepts
- .pb7
- wide platform support

## Email certs

- use cryptography in an email platform
- use public key of reciever to encrypt
- use your private key to decrypt
- digital signatures

## User certs

- associate a user with a cert
- use as additional authentication
- integrate onto smart cards
