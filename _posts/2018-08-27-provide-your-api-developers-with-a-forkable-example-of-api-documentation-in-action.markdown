---
published: true
layout: post
title: >-
  Provide Your API Developers With A Forkable Example of API Documentation In
  Action
date: 2018-08-27T09:00:00.000Z
tags:
  - API Evangelist
  - Documentation
  - Templates
  - Definitions
image: >-
  https://s3.amazonaws.com/kinlane-productions/va-working/va-demo-swagger-ui-documentation.png
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>[I responded about how teams should be documenting their APIs when they have both legacy and new APIs the other day](https://apievangelist.com/2018/08/24/how-should-teams-be-documenting-their-are-new-and-legacy-apis/). I wanted to keep the conversation thread going with an example of one possible API documentation implementation. The best way to deliver API documentation guidance in any organization is to provide a forkable, downloadable example of whatever you are talking about. To help illustrate what I am talking about, I wanted to take one documentation solution, and publish it as a GitHub repository.

I chose to go with a simple OpenAPI 3.0 defined API contract, driving a Swagger UI driven API documentation, hosted using GitHub Pages, and [managed as a GitHub repository](https://github.com/va-working/openapi-documentation). In my story about how teams should be documenting their APIs, I provided several API definition formations, and API documentation options--for this walk-through I wanted to narrow it down to a single combination, providing the minimum(alist) viable options possible using OpenAPI 3.0 and SwaggerUI. Of course, any federal agency implementing such a solution should wrap the documentation with their own branding, similar to the [City Pairs API prototype out of GSA](https://gsa.github.io/prototype-city-pairs-api-documentation/api-docs/), which [originated over at CFPB](http://cfpb.github.io/api/ccdb/).

I used the VA Facilities API definition from the developer.va.gov portal for this sample. Mostly because it was ready to go, and relevant to the VA efforts, but also because it was using OpenAPI 3.0--I think it is worth making sure all API documentation moving forward supports is supporting the latest version of OpenAPI. [The API documentation is here](https://va-working.github.io/openapi-documentation/), the [OpenAPI definition is here](https://github.com/va-working/openapi-documentation/blob/master/openapi/openapi.json), and the [Github repository is here](https://github.com/va-working/openapi-documentation), showing what is possible. There are plenty of other things I'd like to see in a baseline API documentation template, but this provides a good first draft for a true minimum viable definition.

The goal with this project is to provide a basic seed that any team could use. Next, I will add in some other building blocks, and implementation a ReDoc, DapperDox, or WSDLDoc version. Providing four separate documentation examples that developers can fork and use to document the APIs they are working on. In my opinion, one or more API documentation templates like this should be available for teams to fork or download and implement within any organization. All API governance guidance like this should have the text describing the policy, as well as one or many examples of the policy being delivered. Hopefully this projects shows an example of this in action.
