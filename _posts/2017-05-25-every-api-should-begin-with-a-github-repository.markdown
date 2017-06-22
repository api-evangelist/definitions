---
title: Every API Should Begin With A Github Repository
date: 2017-05-25 14:00:00 Z
tags:
- Definitions
- Github
- Design
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/open-referral/open-referral-github-repo-api-spec.png
---

<p><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/open-referral/open-referral-github-repo-api-spec.png" align="right" width="40%" style="padding: 15px;"
 /></p>[I'm working on my API definition and design strategy for my human services API work](http://apievangelist.com/2017/05/24/my-api-design-checklist-for-this-version-of-the-human-services-data-api/), and as I was doing this [Box went all in on Opening](http://apievangelist.com/2017/05/22/box-goes-all-in-on-openapi/), adding to the number of API providers I track on who not just have an OpenAPI but they also use Github as the core management for their API definition.

Part of my API definition and design advice for human service API providers, and the vendors who sell software to them is that they have an OpenAPI and JSON schema defined for their API, and share this either publicly or privately using a Github repository. When I evaluate a new vendor or service provider as part of the Human Services Data API (HSDA) specification I'm beginning to require that they share their API definition and schema using Github--if you don't have one, I'll create it for you. Having a machine-readable definition of the surface area of an API, and the underlying schema in a Github repo I can checkout, commit to, and access via an API is essential.

Every API should begin with a Github repository in my opinion, [where you can share the API definition, documentation, schema](https://openreferral.github.io/api-specification/definition/), and have [a conversation around these machine readable docs using Github issues](https://github.com/openreferral/api-specification). Approaching your API in this way doesn't just make it easier to find when it comes to API discovery, but it also makes your API contract available at all steps of the API design lifecycle, from design to deprecation.