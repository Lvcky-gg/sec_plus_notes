# Managing Security

## Geographical Considerations

- legal
- offsite backups
- offsite recovery
  - hosted in another location, outside of the scope of disaster
  - travel considerations for support staff

## response and recovery controls

- incident response and recovery has become commonplace
- incident response plan should be established
  - documentation is critical
  - identify the attack
  - contain the attack
- limit the impact of an attacker
  - limit exflitration
  - limit access to sensitive data

## SSL/TLS inspection

- commonly used to examine outgoing SSL/TLS
  - secure sockets layer/transport layer Security

## Trust me, I'm SSL

- your browser contains a list of trusted CAs
- your browser doesn't trust a web site unless a CA has signed the web server's encryption cert
- the CA has ostensibly performed some checks
  - validated against the DNS record
- your brother checks the web server's certificate

## Hashing

- represent data as a short string of text
- one-way trip
- verify a downloaded document is the same as the original
- can be a digital signature
- hopefully wont have a collision

## API considerations

- Application Programming Interface
- secure and harder the login page
  - Don't forget the API
- On-path attack
  - Intercept and modify API messages, replay API commands
- DDoS
  - One bad API call can bring down system

## API security

- Authentication
  - limit API access legitimate  users
  - over secure protocols
- Authorization
  - API should not allow extended access
  - Each user has a limited role
  - a read-only user should not be able to make changes
- WAF(Web Application Firewall)
