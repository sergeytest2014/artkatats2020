# Asynchronous communication between inventory points

* Status: accepted

## Context and Problem Statement

What kind of communication be used between inventory points

## Decision Drivers 

* Inventory points should be operable without being connected to the information system
* Some inventory points (like partner's Cafe) may report payments and inventory changes once a day

## Considered Options

* asynchronous communication between inventory points and the information system.
* synchronous communication.

## Decision Outcome

Chosen option: "Microservices", because it provides better flexibility for implementing parts of the system by different team/contractors and integrating third-party services.

### Positive Consequences

* Inventory points can work for some period without being connected to the information system.
* Inventory points become more independent from the informational system and can be implemented more freely using different technology or accommodating existing solutions that partners have.

### Negative Consequences 

* The actual inventory information will be lagging in the information system. That 
* Not possible to use ACID transaction to keep data consistency that makes code more complicated for implementing eventually consistency. 

## Pros and Cons of the Options

### [asynchronous]

* Good, because inventory points can work without being connected to the information system. 
* Bad, because it requires implementing more complex logic.
* Bad, data actuality is always lagging the real state.

### [asynchronous]

* Good, because it is simple to implement.
* Good, because it is simple to keep consistent inventory data.
* Bad, because inventory point must be always connected to the information system.
* Bad, because it might not be possible to implement asynchronous  mode for 3d-party program that partners are used.
