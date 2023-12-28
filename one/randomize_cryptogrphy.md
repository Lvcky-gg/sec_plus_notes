# Randomizing Cryptography

## Cryptographic Nonce

- Arbitrary number: used once
- A random of pseudo-random number: cant be reasonably guessed
- use a nonce during login process

## Initialization Vector

- Type of nonce: used for randomizing an encryption scheme

## Salt

- a nonce that is commonly associated with password randomization
- passwords should always be salted: each user gets a different salt
- If a password's database is breached, you cant correlate any passwords
