# INF-6: Use Traefik

Date: 26-06-2024


## Status

Accepted


## Context

We want to use proxy server to enhances security content, use the TLS protocol, and 
load balancing. 


## Decision

We will use Traefik to set up the TLS easily for all our environments, and to act as ingress
points of our different applications.



## Consequences

We will need to configure properly Traefik as part of our infrastructure, resulting in added a
complexity for our build and deployments.