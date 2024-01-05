# Forensic Data Acquisition

## Order of volitility

- CPU registers, CPU cache
- router tables, ARP cache, process table, kernal stats, memory
- temp file systems
- disk
- remote logging and monitoring data
- physical configuration, network topology
- archival media

## Disk

- copy everything on a storage drive
- drive image prep: power down to prevent changes, remove storage drive
- connect to imaging device
- forensic clone : bit by bit copy, preserve all data

## Random Access Memory(RAM)

- difficult target to capture, changes constantly
- memory dump: grab everything in active RAM
- important data includes browsing history, clipboard info, encryption keys, command keys

## SWAP / pagefile

- used by some OS
- a place to store ram when memory is depleted
- can also contain parts of an application
- contains data similar to RAM dump

## Operating System

- OS files and data
- core OS
  - executables
- other data such as logged in users, open ports, processes

## Device

- mobile device and tablets
- capture data with backup file and transfer to USB

## Firmware

- extract the device Firmware
- specific to platform

## Snapshot

- generally associated with a VM
- point in time
- incremental between snapshots
- contains all files and info about a VM

## Cache

- store data for a user
- can contain specialized data
- some data may not be used

## network

- gather info about and from a network
- inbound and outbound sessions
- packet data
- third party devices can capture

## Artifacts

- digital items left behind
- locations may be in logs, flash memory, recycle bin etc
