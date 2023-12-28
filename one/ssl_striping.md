# SSL Striping / HTTP downgrade

- combines on-path attack with a downgrade attack
- difficult to implement but has a high return
- attacker must sit in between the middle of a conversation: proxy server, ARP spoof, rogue access point
- victim does not see significant problem
- works on SSL and TLS

## SSL and TLS

- SSL(Secure Socket Layers)2.0 - deprecated
- SSL3.0: vulnerable to POODLE, deprecated
- TLS1.0(Transport Layer Security): can downgrade to SSL3.0
- TLS1.1:deprecated
- TLS 1.2 - 1.3 : modern standard
