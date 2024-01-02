# Application Security

## Secure Coding Concepts

- balance of time and quality
- test, QA
- vulnerabilities will be found

## Input Validation

- what is the expected input?
- validate for this
- document all input methods
- check and correct all input types(normalization)
- fix any data with improper input
- fuzzers will find what you miss, don't let them

## Dynamic analysis

- many different options
- send random input to applications
- looking for something out of the ordinary

## Fuzzing Engines and Frameworks

- very time and resource heavy

## Secure Cookies

- cookies: Information stored on your computer by the browser
- used for tracking, personalization, session management
- not executable
- secure cookies have a Secure attribute secure
  - only send over HTTPS
  - sensitive stuff is not to be saved in a cookies

## HTTP Secure Headers

- additional layer of security
- enforce HTTPS communication
- only allows scripts, stylesheets, or images from the local site
- prevents XSS attacks

## Code Signing

- an app is deployed
- the app can be digitally signed by the author

# Allow list, deny list

- any app can be dangerous
- security policies can block an app's execution
- allow list : nothing runs unless approved
- deny lists: blocks any app on the bad list

## Static code analyzer

- Static Application Security Testing(SAST)
- many vulnerabilities found easily
- not everything can be identified through analysis
