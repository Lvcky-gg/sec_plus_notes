# Log Manager

## Syslog

- standard for message logging
- usually a central logging reciever
- each log is labelled
- syslog daemon options
  - Rsylog Rocket Fast System for Log Processing
  - syslog a popular daemon with additional filtering and storage options
  - nxlog collection from many diverse log types

## journalctl

- linux has a lot of logs
- system logs are stored in binary format
- journalctl provides a method for querying the system journal

## Bandwidth monitors

- fundamental network statistics
- many different ways to gather this method
  - SNMP, NetFlow, sFlow, IPFIX protocol analysis, software agent
- identify fundamental issues

## metadata

- metadata : data that describes other data source
- email : header details, sending servers, destination address
- mobile
- web
- files

## NetFlow

- gather traffic statistics from all traffic flows
- netflow : standard collection methods, many products and options
- probe and collector
- usually seperate reporting app

## IPFIX

- IP flow information export
  - newer netflow based environment
- from netflow v9
- flexible data support

## sFlow

- sampled flow
- usually embedded in the infrastructure
- relatively accurate statistics

## Protocol analyzer output

- solve complex application issues
- gather packets on the network
- view detailed traffic information
