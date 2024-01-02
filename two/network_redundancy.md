# Disk Redundancy

## Redundancy

- duplicates parts of the system
- maintain uptime
- no hardware failure
- no software failure
- no system failure

## Geographical dispersal

- bad things can happen in local area

- disperse tech to multiple geographies

- data centers might be part of normal operations

- may be part of disaster recovery centers

## Disk redundancies

- multipath I/O(Input/Output)
- RAID
- multiple drives create Redundancy

## RAID

- 0: Striping without parity, high performance, no fault tolerance
- 1: mirroring, duplicates data for fault tolerance, twice the disk space
- 5: striping with parity: fault tolerant, requires additional disk
- 0 + 1, 1 + 0, 5 + 1: multiple RAID, cobine for redundancy
