# Injection Attacks

## Code Injection

- adding your own information into a data stream
- Enabled because of bad programming: should properly handle input and output
- many data types: HTML, SQL, JSON, XML, LDAP, QML etc...

## SQL injection

- Structured Query Language: very common query language for relational databases
- SQL Injection modifies SQL request: this is very bad, don't let this happen

## XML Injection or LDAP Injection

- XML: Extensible Markup Language
- XML Injection: modifying XML request
- LDAP: Lightweight Directory Access Protocol (made for telecom, used everywhere)
- LDAP Injection: modify LDAP requests

## DLL Injection

- Dynamic-Link Library
- windows library containing code and data
- inject a DLL and have an application run a program
