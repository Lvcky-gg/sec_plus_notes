# Request Forgeries

## Cross-Site Requests

- Cross-Site requests are Common and Legitimate

## The Client and the Server

- Webpage consists of client-side code and server side code
- client side renders page: HTML, CSS, JavaScript
- server side performs client requests

## Cross-site request forgery

- one click attack, session riding- XSRF, CSRF
- takes advantage of trust in web application
- web site trusts browser
- requests are made without consent or knowledge
- Significant development oversights: anti-forgery techniques missing, cryptographic token is needed, CORS is not implemented

## Server-side request Forgery(SSRF)

- Attacker finds a vulnerable web app and sends request to app: web server performs request on behalf of the Attacker
- caused by bad programming: Don't trust user input, server should validate session
- critical but rare vulnerability
