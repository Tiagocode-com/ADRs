# INF-3: [Website] Use Leptos rs framework

Date: 24-06-2024


## Status

Accepted


## Context

We want to choose a Rust frontend web-framework to develop the UI part of
our application (portfolio and blog).


## Decision

We will use [Leptos](https://leptos.dev/) as a frontend framework for the project. Leptos is
one of the emergent Rust frameworks for the web, and that aligns correctly with our decision
of learn new technologies on the Rust ecosystem.  

Additionally, Leptos provides a cutting-edge web framework with a great performance, server 
side rendering (without hydration), client side rendering, components patterns, etc.


## Consequences


- At the moment of writing this ADR, Leptos is a small framework maintained by unpaid 
contributors. So, it is possible that the project being abandoned in the future if it doesn't get the proper reception from Rust community.

- The learning curve of the framework and the expertise of our team. Those will slow down 
the development process. 