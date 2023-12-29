# Protecting data

- a primary job task
- data is everywhere
- protections include: encryption and security policies

## Data sovereignty

- data that resides in a nation is subject to that nation's laws
- legal monitoring and court orders

# - laws may prohibit where data is stored

- GDRP(General Data Protection Regulation)
- data collected on EU citizens must be stored in the EU

# - complex mesh of legalities

## Data masking

- data obfuscation
  - hide some of the original data
- protects PII
- may only be hidden from view
- many different techniques

## Data encryption

- encode info in unreadable data
- this is a two way street and is reversible
- confusion
- diffusion

## data at rest

- data that is stored
- encrypt this
- apply permissions

## data  in transit

- data transmitted over network
- not alot of protection while it travels
- network based protections such as firewall or IPS
- provide transport encryption like TLS or IPsec

## data in use

- data is currently in memory
- it is almost always decrypted
- attackers can steal this from RAM

## Tokenization

- replace sensitive data with non-sensitive placeholder
- common with credit card processing
- this is not encryption or hashing

## Information Rights Management (IRM)

- control how data is used
- restrict data access to unauthorized persons
- each user has their own sets of Rights
