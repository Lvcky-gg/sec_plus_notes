# Password Attack

- some passwords are stored in plaintext. this is rare
- Do NOT store passwords in plaintext; anyone can get it.
- If an app does this, don't use it

## Hashing a password

- Hashes are data represented as a fixed-length string, a fingerprint
- hopefully shouldn't have a collision(different inputs resulting in the same hash)
- not reversible
- for the love of G-d please use a salt with this.
- common algos include SHA and MD5

## The password file

- different across OS and apps, use of different algos

## Spraying attack

- you are likely to be locked out if you keep trying to guess a password
- this will take some common passwords, try them then move to another account and use the same passwords

## Brute force

- try every possible password until the hash matches
- this can take ages, hope you have a good gpu
- you can brute force a hash until it matches if you have access to it. this prevents lockouts

## Dictionary attacks

- use a dictionary to find common words
- uses a common wordlist
- it takes time
- will substitute letters with symbols and numbers

## Rainbow tables

- a prebuilt set of Hashes
- saves time and money, alot faster
- need different tables for different hashing methods

## Salting

- salt: random data added to password when hashing
- every user gets their own salt. It is likely stored with the password. Take it
- rainbow tables are ineffective if something has been salted
- it also slows down brute force

## When hashes get out, its time for a new algo
