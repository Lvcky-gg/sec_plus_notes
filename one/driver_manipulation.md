# Driver Manipulation

## Malware hide and go seek

- anti-virus is good at identifying known attacks
- Zero-day attacks can hide from this

## Your drivers are powerful

- they interact between hardware and OS
- often trusted
- great target for exploit
- hardware interactions can contain sensitive info

## Shimming

- filling a space in the middle of two objects
- windows has a Shim to interact between versions
- Malware authors can write their own shim to get around security(UAC)

## Refactoring

- Metamorphic malware, a different program each time it is downloaded
- it may appear different each time
- can intelligently redesign itself
- difficult to match with signature based detection
