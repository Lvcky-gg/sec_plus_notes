# Wireless Authentication protocols

- many auth methods

## EAP (Extensible Authentication Protocol)

- many different ways to authenticate based on RFC standards
- EAP integrates with 802.1x

## IEEE 802.1x

- port based network access control (NAC)
- no access until you authenticate
- used in conjunction with access database: RADIUS, LDAP, TACAS+

## IEEE 802.1x and EAP

- supplicant
- authenticator
- authentication server

## EAP-FAST

- EAP flexible authentication via secure training
- authentication server and supplicant share a protected access credential
- supplicant recieves the pac
- supplicant and AS mutually authenticate and negotiate a transport layer security (TLS)
- user authentication occurs over the tls tunnel
- need a radius server

## PEAP

- protected extensible authentication protocol
- also encapsulates EAP in a TLS tunnel
- user authenticates with MSCHAPv2
- user can also authenticate with a GTC

## EAP TLS

- EAP Transport Layer Security
- strong security, wide adoption
- requires digital certs on the AS
- relatively complex

## EAP-TTLS

- EAP tunneled transport layer security
- requires digital cert on the AS
- use any auth methods in the tunnel

## rADIUS Federation

- use RADIUS with federation
- use 802.1x authentication methods and radius on the backend
- driven by eduroam
