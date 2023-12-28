# Other Application Attacks

## Memory Vulnerability

- manipulating memory can be hard to accomplish, but beneficial
- memory leak can exploit unused memory, grows in size, eventually uses all memory and causes a system crash. This can be prevented by a programmer deallocating memory when it is no longer needed.
- NULL pointer dereference is a programming technique that references a portion of memory, if you reference nothing your program will crash
- Integer overflow is when large numbers are placed into small sized space

## Directory Traversal

- Directory or path traversal is when you read files from a web server that are outside of the website's directory. Users should not be able to browse the Windows folder
- Web server software vulnerability wont stop users from browsing past root
- takes advantage of poorly written code

## Improper Error Handling

- Errors happen, they should be caught
- error messages should not share too many details, network info, memory dump, stacktraces or DB dumps.
- this is easy to fix, just write idiomatic code

## Improper input Handling

- many apps accept user input, this must be considered
- All input is to be considered evil
- Check everything, trust nobody
- allowing invalid input can lead to SQL injection, buffer overflow, denial of service, etc
- it takes a lot of work to find potentially flawed input validation

## API Attacks

- API - Application Programming Interface
- attackers can find vulnerabilities here

## Resource Exhaustion

- A special DOS attack
- ZIP bomb: 42kb zip file that decompresses to 4.5 petabytes anti-virus can detect these
- DHCP Starvation: a flood of IP address requests, MAC changes each time, DHCP server runs out of addresses, rate limit these Attacks
