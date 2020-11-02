# Microservices architecture

* Status: accepted

## Context and Problem Statement

Which architecture style to choose for this information system.

## Decision Drivers 

* Important to deliver MVP solution quickly
* It is not required to implement comprehensive solution at once. The system can be developer in steps by funtionality blocks.
* Development of functionality blocks can be significantly distanced in time and the need of particluar functionality may changed frequently.
* Whenevever possible the existing paid or open source components/services should be used.

## Considered Options

* Microservices
* Monolith

## Decision Outcome

Chosen option: "Microservices", because it provides better flexibility for implementing parts of the system by diffent team/contractors and integrating third-party services.

### Positive Consequences

* More simpler to integrate existing 3d-party components that can be written on different programming languages.
* More simpler to hire developer team or individual contractors to build required functionality as independent microservice.

### Negative Consequences 

* Harder to support this zoo of different services.
* Harder to design the full system and keep it consistan.

## Pros and Cons of the Options

### [Microservices]

* Good, because it can be more easy to integrate 3d-party services
* Good, because services can be developed independently in different time and by different developers.
* Bad, because requires more efforts in managing of many services.

### [Monolith]

* Good, because quicker development that is important for this stage of the strartup.
* Good, because can keep minimal set of used technologies.
* Bad, because lock in for a certian development team and tech.
