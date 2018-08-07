---
published: true
layout: post
title: Working With My OpenAPI Definitions In An API Editor Helps Stabilize Them
date: 2018-08-07T09:00:00.000Z
tags:
  - API Evangelist
  - Design
  - Stability
  - Validation
  - Definitions
image: >-
  https://s3.amazonaws.com/kinlane-productions/openapi/swagger-editor-screenshot.png
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>I'm deploying three new APIs right now, using a new experimental serverless approach I'm evolving. One is a location API, another providing API access to companies, and the third involves working with patents. I will be evolving these three simple web APIs to meet the specific needs of some applications I'm building, but then I will also be selling retail and wholesale access to each API once they've matured enough. With all three APIs of these APIs, I began with a simple JSON schema from the data source, which I used to generate three rough OpenAPI definitions that will acts the contract seed for my three services.

Once I had three separate OpenAPI contracts for the services I was delivering, I wanted to spend some time hand designing each of the APIs before I imported into AWS API Gateway, generating Lambda functions, loading in Postman, and used to support other stops along the API lifecycle. I still use [a localized version of Swagger Editor for my OpenAPI design space](https://editor.swagger.io/), but I'm working to migrate to [OpenAPI-GUI](https://mermade.github.io/openapi-gui/) as soon as I can. I still very much enjoy the side by side design experience in Swagger Editor, but I want to push forward the GUI side of the conversation, while still retaining quick access to the RAW OpenAPI for editing.

One of the reasons why I still use Swagger Editor is because of the schema validation it does behind the scenes. Which is one of the reasons I need to learn more about [Speccy](http://speccy.io/), as it is going to help me decouple validation from my editor, and all me to use it as part of my wider governance strategy, not just at design time. However, for now I am highly dependent on my OpenAPI editor helping me standardize and stabilize my OpenAPI definitions, before I use them along other stops along the API lifecycle. These three APIs I'm developing are going straight to deployment, because they are simple datasets, where I'm the only consumer (for now), but I still need to make sure my API contract is solid before I move to other stops along the API lifecycle.

Right now, loading up an OpenAPI in Swagger Editor is the best sanity check I have. Not just making sure everything validates, but also making sure it is all coherent, and renders into something that will make sense to anyone reviewing the contract. Once I've spend some time polishing the rough corners of an OpenAPI, adding summary, descriptions, tags, and other detail, I feel like I can begin using to generate mocks, deploy in a gateway, and begin managing the access to each API, as well as the documentation, testing, monitoring, and other stops using the OpenAPI contract. Making this manual stop in the evolution of my APIs a pretty critical one for helping me stabilize each API's definition before I move on. Eventually, I'd like to automate the validation and governance of my APIs at scale, but for now I'm happy just getting a handle on it as part of this API design stop along my life cycle.
