# Cross-Site Scripting Xss

- Xss
- Common web application development error
- malware that uses JavaScript

## Non-persistent (reflected) Xss attack

- web site allows scripts to run in user input: search box is Common
- attacker emails a link that takes advantage of this vulnerability
- sends cookies and creds to attacker
- Script embedded in URL executes in victim's browser as if it came from server
- attackers use info to steal victim's identity without their knowledge

## Persistent(stored) xss attack

- Attacker posts malicious message to social media: includes a payload
- it is now persistent, everyone can get it
- no specific target, everyone can get hit
- it can spread very quickly

## Protection

- be careful with links
- you could consider disabling javaScript, but keep in mind that the modern web will be inoperable. Better option is to control with extension
- you could keep browser and apps up to date
- validate input: WEB DEVS PAY ATTENTION HERE
