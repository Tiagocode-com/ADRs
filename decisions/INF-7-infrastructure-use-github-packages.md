# INF-7: Use GitHub packages

Date: 26-06-2024


## Status

Accepted


## Context

We want to use a registry system to store and distribute the images of our applications. It will ensure the 
version control, access control. Additionally, it will facilitate consistent and secure deployments across different
environments.


## Decision

We will use GitHub Packages as image registry because is a popular tool, and it is a feature that already offers
our repository management platform (GitHub).

We also considered the following alternative solutions:

* [Docker Hub](https://hub.docker.com/) (not selected, it offers a paid plan).


## Consequences

No significant consequences.