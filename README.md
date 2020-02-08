# Microservices 

Buys you options - not a panacea, isn't necessarily fit for all projects

What's main factors advocating microservices -

* Machines getting cheaper - more machines may cost not too much (for microservices) compared to one big machine (for monolith)
* Networks are faster, more reliable - latency in systems interaction has reduced
* 

## Pros
* Quick deployment cycle - no dependency on other systems
* Scalability at a mico level (components/microservices), not for the whole system (monolith)
* Choice of languages - different microservices can be developed using different languages, easier to upgrade/move to different technology 

## Cons
* Difficult to have atomic transactions, need to look for alternatives
* Network latency is always going to be more than communication latency within monolith components.
* Network failures are inevitable. More components, moving parts means more possible points of failure
* Always more expensive than monolith system - need more hardware and development resources
* More complex technology


## Main considerations while identifying prospective microservices
* Independent deployability
* Based on a business domain
* Vertical slice of frontend, service and db
*
