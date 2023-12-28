# MAC Flooding and Cloning

## The MAC Address

- Ethernet Media Access Control Address
- 48 bits long

## LAN switching

- forward or drop frames based on destination MAC
- Gather a constantly updating list of MAC addresses

## Learning the MACs

- switches examine incoming traffic
- adds unknown MAC addresses to the MAC table

## MAC Flooding

- the MAC table is a certain size, its only so big
- attackers start sending traffic with different source MAC addresses
- the table fills
- it turns the switch into a hub: all traffic is transmitted to interfaces with no interruptions in flow
- attacker can now capture all network traffic
- it can be restricted in the switch's port security settings

## MAC cloning/spoofing

- an attacker changes their MAC address to match the MAC address of an existing device
- Circumvents filters
- Create a DoS
- easilly manipulated via software
