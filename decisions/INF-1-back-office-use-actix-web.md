# INF-1: Back-office - Use Actix Web framework

Date: 23-06-2024


## Status

Accepted


## Context

We want to use a Rust web-framework to develop our back-office solution. So we don't need
to write routing system, environment config support, database management, and many other
important things from scratch. And more important, that we can speed up the development process.


## Decision

We will use the [Actix Web](https://actix.rs/) as web-framework solution for the back-office. 
This aligns well with the knowledge that members acquired in the book "From Zero 2 Production".

We also considered the following alternative solutions:

* [Rocket.rs](https://github.com/rwf2/Rocket/tree/v0.5.1) (not selected, because the framework has 
slow releasing cycles, and it is mostly driven by a single owner).


## Consequences

* We will benefit with the most of the features already offer by the framework like Type Safe,
Logging, Routing system, Extractors, Responders, Form Handling, etc.

* Some features like templates are not already integrated with the framework, we can "easily" extend
the framework to add the feature thought, but it will require us more effort.


