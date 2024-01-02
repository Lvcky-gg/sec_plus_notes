# Cryptographic Keys

- most things are known about cryptography
- key determines the output
- keep key private

## key strength

- larger keys are more secure
- symmetric encryption: 128 bit or larger is common
- asymmetric encryption: common to see 3072 bit or larger

## key exchange

- logistical challenge

- out-of-band key exchange

  - dont send symmetric key over the net

- in band key exchange

  - it is on the net
  - uses asymmetric to deliver symmetric

## Real time encryption/decryption

- need for fast security
- share a symmetric key using asymmetric encryption
  - client encrypts a random key with a server's public key
  - server decrypts the shared key
    -this is a session key
- implement session keys carefully

## symmetric key from asymmetric key

- use public key cryptography to create symmetric key

## Traditional web server encryption

- SSL/TLS uses encryption keys to protect web server communications
  - based on RSA key pair
- one point of failure for all of your web encryption

## perfect forward secrecy(pfs)

- change the method of key exchange
- elliptic curve or diffy-hellman ephermal
- can't decrypt with private server key
- pfs requires more compute power
- a browser must compute pfs
