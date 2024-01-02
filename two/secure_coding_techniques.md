# Secure Coding

## concepts

- balance between time and quality
- test test test
- vulnerabilities will eventually be found

## Stored procedures

- SQL databases
- client requests con be complex
- stored procedures limit client interactions

## Obfuscation/camouflage

- obfuscate: make something normally understandable hard to understand
- take readable code and turn it into nonsense
- helps prevent search for security holes

## code reuse/dead code

- reuse: using old code to build new applications/ copy and paste
- if code has vulnerabilities, reuse in other applications means they have it too
- dead code: stuff happens but isn't used
- all code can be vulnerable

## Input Validation

- server-side Validation: helps protect against malicious user
- client-side validation: using the app to make client-side decisions
- use both, but especially server-side

## Memory-management

- be aware of how memory is used
- never trust data input
- buffer overflows are a huge risk
- some built ins are insecure

## Data Exposure

- sensitive data
- make sure you handle it well:
  - encrypted when stored?
  - across network?
  - on screen?
- all input and output is important

## version control

- make a change and track the change
- common: git
- useful for security to compare versions over time
