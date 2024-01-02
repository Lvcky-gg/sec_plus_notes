# Authentication Methods

## Directory Services

- keep all of an organizations usernames and passwords in a single database
- large distributed database
- all auth requests reference this directory
- access via Kerberos or LDAP

## Federation

- provide network access to others
- third-party can establish federated network
  the third-parties must establish a trust relationship

## Attestation

- prove the hardware is yours
- easy when its just your computer
- remote Attestation
  - device provides operational report to validated server
  - encrypted and signed with TPM
  - an IMEI or other unique hardware component can be included in report

## Short Message Service(SMS)

- text messaging
- login factor can be sent via SMS to predefined number
- security issues
  - phone number can be reassigned to different phone
  - SMS messages can be intercepted

## TOTP

- Time-based One-Time Password algorithm
  - uses a secret key and time of day
  - no incremental counter
- secret key is configured ahead of time
- synchronized via NTP
- ususally increments every 30 seconds
- relatively common

## HOTP

- One-Time passwords
- use once, never again
- once a session
- HMAC based One Time Password algorithm
  - keyed-hash messages authentication code
  - based on secret key and counter
- Token-based authentication
- hardware and software tokens available

## phone call

- similar issues as SMS

## Static codes

- auth factors that don't change
- PIN code
- password or phrase

## Smart cards

- integrated circuit card - contact or contactless
- must have physical card to provide digital access
- multiple factors: pin or fingerprint for example
