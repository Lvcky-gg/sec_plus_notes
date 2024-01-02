# Stream and Block Ciphers

## Stream Ciphers

- encryption can be done one byte at a time
- used with symmetric encryption
- starting state should not be the same twice

## Block Ciphers

- encrypt fixed length groups
- mode of operation: defines method of encryption
- block size is a fixed size

## ECB(Electronic Code Book)

- simplest encryption mode
- each block is encrypted with the same key

## CBC(Cipher Block Chaining)

- popular mode of operation
- each plaintext block is XORed with previous siphertext block

## CTR(counter)

- cipher block acts like strean cipher
- canbe any size

## GCM(Galois/Counter Mode)

- encryption with authentication
- minimum latency, minimum operation overhead
- commonly used in packetized data
