# Application Hardening

- minimize attack surface
- remove potential for all known vulnerabilities
- spme hardening may have compliance mandates
- resources
  - CIS
  - SANS
  - NIST

## open ports and services

- every port is a possible entry point
- control access with a firewall
- unused or unknown services
- applications with broad ranges
- use NMAP or similar port scanner to verify

## Registry

- primary configuration database for Windows
- useful to know what an application modifies

## Disk Encryption

- prevent access to application data files
- full disk encryption(FDE)
- Self-encrypting drive(SED)
- Opal Storage Specification

## Operating System Hardening

- many and varied OS
- update
- user accounts
  - min pw lengths and complexity
  - account limitation
- network access and security
- monitor and secure

## Patch Management

- incredibly important
- monthly updates
- third-party updates
- auto update
- emergency out of band updates(ZERO DAY)

## Sandboxing

- apps cannot access unrelated resources
- used during development commonly
- used in many different deployments
