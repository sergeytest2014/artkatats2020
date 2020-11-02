# Progressive web app (PWA)

* Status: accepted

## Context and Problem Statement

Solution requires to have an ability to check specific meal availability on mobile devices.

## Decision Drivers 

* Current required functionality is quite simple.

## Considered Options

* PWA
* Mobile Application

## Decision Outcome

Chosen option: "PWA" because it cheaper/simpler to implement.

### Positive Consequences

* The mobile functionality completely follows web version, there's no need to develop mobile application for different platforms.
* May resemble a "real" mobile application on modern version of mobile platforms.
* Will work for old smartphones

### Negative Consequences 

* In distant feature it might require rebuilding the functionality as a mobile application.

## Pros and Cons of the Options

### [PWA]

* Good, because it can be developed along with web site.
* Good, because it can work on old mobile devices as a website.

### [Mobile Application]

* Good, because may support native way and look on a specific mobile platform.
* Bad, because required additional work and additional support for different mobile platform and versions.
