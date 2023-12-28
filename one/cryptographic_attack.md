# CryptoGraphic Attacks

- is your encrypted data actually secure?
- there are ways to undo the security, even without the key.

## Birthday Attacks

- This is based upon the paradox that out of 30 people, there is a 70% chance that two share a birthday.
- this is a hash collision attack that works on the assumption that two values must share a hash
- An attacker will generate hashes until one matches the correct one

## Collisions

- Hash digests are supposed to be unique, but you never know
- the same hash shouldn't ever be created

## MD5 hash

- Message digest Algorithm 5
- April 1992, collisions identified 4 years later

## Downgrade Attack

- instead of good encryption, use bad encryption....forces system to downgrade security
- 2014 TLS vulnerability POODLE on-path attack that reversed clients to SSL 3.0. Modern browsers can no longer revert to SSL3.0. Use a modern browser by the way.
