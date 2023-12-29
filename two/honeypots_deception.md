# Honeypots and Deception

## Honeypots

- attract the bad guys and trap them
- the attacker is likely a machine
- honeypots create a virtual world to explore

## Honeyfiles and honeynets

- honeynets
  - More than one honeypot on a network
  - more than one source of information
  - [Stop Spammers](https://projecthoneypot.org)
- Honeyfiles
  - bait for honeynets
  - alert is sent if the file is accessed
  - virtual bear trap

## Fake Telemetry

- Machine Learning
- Train the machine with actual data
- send the machine learning model fake Telemetry

## DNS sinkhole

- a DNS that hands out incorrect IP address
  - Blackhole DNS
- this can be bad: attacker can redirect users to the malicious site
- this can be good
  - redirect known malicious domains to a benign IP address
  - Watch for any users hitting the IP address
  - those devices are infected
- can be integrated with firewall
