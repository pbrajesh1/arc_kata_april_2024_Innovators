# Title: Application will use event-driven microservices architecture

## Status

APPROVED

## Context

We wanted to choose a suitable architecture style for our application.


## Decision

* Once we started analysing the requirement, we came up with multiple independent services as well as both sync and asyn interactions.
* Also, our analysis of the NFRs also led us towards microservces and eevent-driven architecture style.
* Hence we shall use both microservces and event-driven architecture style.


## Consequences

#### Positive
* Microservices enables extensibility: new functions can be implemented by creating new capabiltiy services
* Scalability: there are many methods to orchestrate services based on changing load
* Usuability: By making the architecture extensible, we can make it easier to add new functionality
* Async communication: Using event-driven arctitecture will add in prioper handling of async communications.

#### Negative
* Costs are quite high due to unused compute time, etc.
* Additional complexity: troubleshooting is harder


[Home Page](../README.md) | [ADR Home Page](../Architecture_Decision_Reports)
