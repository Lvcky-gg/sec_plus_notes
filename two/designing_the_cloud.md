# Designing the Cloud

- On-demand computing power
- elasticity
- Application also scale

## Thin Client

- basic application usage
  - applications run on a remote server
  - Virtual Desktop Infrastructure(VDI)
  - Desktop as a Service(DaaS)
  - local device is a keyboard, mouse and screen

## Virtualization

- Run many different OS on the same hardware
- each application has its own operating system
  - adds overhead and complexity
  - virtualization is expensive

## Containerization

-contains everything needed to run an application

- code and dependencies
- a standardized unit of software
- Isolated process in a sandbox
- Container image
  - standard for portability
  - lightweight
  - secure seperation between applications

## Microservices and API

- monolithic applications
- app contains all decision making processes
  - UI, business logic, data control
- code challenges: large codebase
- APIs
- API is glue for the microservices
- scalable
- resilient
- security and compliance

## Serverless Architecture

- Function as a Service (FaaS)
  - applications are separated into individual, autonomous functions
  - remove OS from equation
- Developer still creates the server-side logic
- May be event triggered and ephermal
- managed by third-party

## Transit Gateway

- virtual private cloud (VPC)
- common to create many VPC's
- now make it secure

## Resource Policies

- assign permissions to cloud resources
- specify which resources can be provisioned(Azure)
  - create a service in a specific region, deny all others
- now ( amazon )
  - allow access to API gateway from an IP address range
- explicitly list the users who can access the resource(Amazon)
  - underlist is associated with resource

## Service integration

- Service Integration and Management(SIAM)
- many different service providers
- every provider works differently
  -SIAM is the integration of these diverse providers
- an evolving set of proceedures and processes

## Transit Gateway

- Virtual Private Cloud(VPC)
  - pool of resources in a public cloud
- common to create many
- connect VPC with a transit gateway and users to VPC
- now secure it
