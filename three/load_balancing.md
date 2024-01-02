# Load Balancing

- distribute the load to multiple servers
- large scale implementations
- fault tolerance

## Load Balancer

- configurable load
- TCP offload
  - protocol overhead
- SSL offload
  - encryption/decryption
- caching
  - fast response
- prioritization
  - QoS
- content switching

## Scheduling

- round robin
  - each server is selected in turn
- weighted round robin
  - prioritized
- dynamic round robin
  - monitor the server load and distribute accordingly

## Affinity

- kinship
- many apps require comms to the same instance

## Active/passive load Balancing

- some servers are Active
- if an active server fails, passive server takes its place
