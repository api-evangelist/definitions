---
title: Zooming Out To The 100K Level Then Back To API Sea Level With OpenAPI And APIs.json
date: 2017-06-15 13:00:00 Z
tags:
- Definitions
- API Evangelist
- HSDA
- HSDS
image: http://kinlane-productions.s3.amazonaws.com/api_evangelist_site/blog/drone_control_sunset.png
---

<p><img src="http://kinlane-productions.s3.amazonaws.com/api_evangelist_site/blog/drone_control_sunset.png" align="right" width="40%" style="padding: 15px;" /></p>I'm wrestling with the different levels of conversations I'm having around [my human services API work](https://openreferral.github.io/api-specification/definition/). Some of my audience are more technical and are pushing for discussion at the granular level, while other parts of my audience are more about the business of things at the 100K. I appreciate these types of projects, but when there are many different conversations going on at many different levels, it is a lot of work to wrestle things into something coherent that everyone involved will appreciate.

One day I'm thinking about which individual fields are required, then next I will considering how multiple human services API integrators will be syndicating and sharing information between clusters of human service API implementations. While I'm relying on Github, and Slack to facilitate conversations that going on, I am ultimately relying on [OpenAPI](https://www.openapis.org/) and [APIs.json](http://apisjson.org) to help me hammer out the contract that will speak to the developers at the granular level but can also communicate the business and political terms of the API contract.  It will describe which fields are required as well as describe the webhooks I need to define how to syndicate and share between implementations.

OpenAPI is pretty focused on helping me with things happening at API sea level, but I'm exploring using APIs.json to help me organize conversations all the way up to the 100K foot level. Things like, where do I signup for my API keys, access partnership levels of access, find the terms of service, or possibly someone to contact and answer a question. Then using the OpenAPI I can publish documentation for developers to understand the surface area of the API (sea level), and while the APIs.json includes a pointer to this discussion, it also provides pointers to other discussions going on around support, communications, changes, privacy, security, so that I can generate documentation for business and partner stakeholders as well. 

I'm working on an example of doing this for [my Open Referral Human Services API](https://openreferral.github.io/api-specification/definition/). An APIs.json + OpenAPI that helps articulate what is happening with any single human services API implementation from sea level to 100K. The trick is I also need to articulate how this will work at scale across clusters of human services API implementations, allowing vendors and partners to syndicate and federate. With everything defined as a machine readable index (using APIs.json and OpenAPI), which can be used to generate very technical API documentation, as well as more business-friendly aspects of operations.