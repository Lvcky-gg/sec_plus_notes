# Hashing and Digital Signatures

## Hashes

- represent data as a short string of text
- one-way trip
- verify downloaded document is the same as te original
- can be digital Signatures
- hopefully wont have collision

## collision

- hash functions take input of any size and make a fixed string
- hash should be unique
- MD5 has a collision problem

## Practical Hashing

- verify a downloaded file
- password storage

## Adding Salt

- salt: random data added when Hashing
- every user gets their own salt
- rainbow tables don't work on salted hashes
- slows down brute force process
- each user gets different hash

## Digital Signatures

- prove message has not changed
- prove the source of the message
- make sure signature isn't safe
- sign with private key
- verify with public key
