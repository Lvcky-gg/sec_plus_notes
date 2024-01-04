# Identity and Access Services

## RADIUS(Remote Authentication Dial-in User Service)

- one of the more common AAA protocols
- supported on alot of devices
- centralize authentication for users
- RADIUS is available on almost any OS

## TACAS

- terminal access controller
  - access control system
  - remote authentication protocols
  - created to control access to dial up lines to ARPANET
- XTACAS = extended tacas
  - cisco tacas
  - additional support for accounting and auditing
- TACAS+
  - latest version of tacas, not backwards compatible
  - more auth requests and response controls

## Kerberos

- network authentication protocol
- auth once, trusted by system
- no need to reauthenticate
- mutual auth of client and server
- developed by MIT in the 80s
- microsoft uses it in windows

## SSO with Kerberos

- auth once
- no constant username and password input
- only works with kerberos

## RADIUS, TACAS+ or Kerberos

- three different ways to communicate
- TACAS+ is probably a cisco device
- kerberos is probably a microsoft device

## IEEE 802.1x

- port based network access control
- used in conjunction with access dbs
