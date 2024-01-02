# Backup Types

- archive attribute
- full = everything
  - all selected data
  - high backup/low restore time
  - archive attribute = cleared
- incremental = all files changed since last incremental Backup
  - new files and files modified
  - low backup/high restore time
  - archive attribute = cleared
- differential = all files changed since last full
  - all modified data since last full
  - moderate backup/moderate restore time
  - archive attribute = not cleared

## Incremental backup

- a full back up is taken first
  -- contains data changed since last full backup and last incremental: usually smaller than full
- restoration requires the full backup and all other incremental backups

## differential

- full backup is taken first
- contains data changed since last backup
- can grow large as data is changed
- full back up and last differential

## Backup Media

- magnetic tape
  - sequential storage
  - 100 GB - mult terabyte per cart
  - easy to ship and store
- disk: faster that mag tape
- copy: useful, may not include versioning

## NAS vs SAN

- Network attached Storage(NAS)
  - connect to a shared stprage across network, file-level access
- Storage area network
  - looks and feels like a local storage device
  - block-level access
  - requires a lot of resiliance

## Others

- cloud
- image(exact replica)

## Backup locations

- offline
- online
