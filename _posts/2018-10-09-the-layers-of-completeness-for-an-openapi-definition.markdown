---
published: true
layout: post
title: The Layers Of Completeness For An OpenAPI Definition
date: 2018-10-09T09:00:00.000Z
tags:
  - API Evangelist
  - Definitions
  - Discovery
  - Documentation
image: 'https://gist.github.com/kinlane/5e52d6063a0744d711795beb6e60365f.js'
---
Everyone wants their OpenAPIs to be complete, but what that really means will depend on who you are, what your knowledge of OpenAPI is, as well as being driven by your motivation for having an OpenAPI in the first place. I wanted to take a crack at articulating a complete(enough) definition for OpenAPIs I create, based upon what I'm needing them to do.

**Info & Base** - Give the basic information I need to understand who is behind, and where I can access the API.
<script src="https://gist.github.com/kinlane/5e52d6063a0744d711795beb6e60365f.js"></script>

**Paths** - Provide an entry for every path that is available for an API, and should be included in this definition.
<script src="https://gist.github.com/kinlane/1aa1a3f492da5f18bc7947b62589c8f8.js"></script>

**Parameters** - Provide a complete list of all path, query, and header parameters that can be used as part of an API.
https://gist.github.com/kinlane/29d0247d6ff4aaa39db4dc793df4a2f9

**Descriptions** - Flesh out descriptions for all the path and parameter descriptions, helping describe an API does.
<script src="https://gist.github.com/kinlane/160ae6aafdf5a5fb7114b5dd2ac37981.js"></script>

**Enums** - Publish a list of all the enumerated values that are possible for each parameter used as part of an API.
https://gist.github.com/kinlane/444731f0214cab5efcc3ae77011823ba

**Definitions** - Document the underlying schema being returned by creating a JSON schema definition for the API.
<script src="https://gist.github.com/kinlane/e833af3e1df40c716289c6cb81a64b88.js"></script>

**Responses** - Associate the definition for the API with the path using a response reference, connecting the dots regarding what will be returned.
<script src="https://gist.github.com/kinlane/01b5805b9d2cf60e163f708b9a8e5916.js"></script>

**Tags** - Tag each path with a meaningful set of tags, describing what resources are available in short, concise terms and phrases.
<script src="https://gist.github.com/kinlane/13331609e54f0dc88383144f08b01f50.js"></script>

**Contacts** - Provide contact information for whoever can answer questions about an API, and provide a URL to any support resources.
<script src="https://gist.github.com/kinlane/0009c35551f94d9dead677b3555ee7ed.js"></script>

**Create Security Definitions** - Define the security for accessing the API, providing details on how each API request will be authenticated.
<script src="https://gist.github.com/kinlane/aa56655a10bda8ee26ced5f98434d4fd.js"></script>

**Apply Security Definitions** - Apply the security definition to each individual path, associating common security definitions across all paths.
<script src="https://gist.github.com/kinlane/2c99e9b3f8382d2ea60a8db838dfdad2.js"></script>

**Complete(enough)** - That should give us a complete (enough) API description.
<script src="https://gist.github.com/kinlane/061f8c83226027c98079aa5fe3857ff2.js"></script>

Obviously there is more we can do to make an OpenAPI even more complete and precise as a business contract, hopefully speaking to both developers and business people. Having OpenAPI definitions are important, and having them be up to date, complete (enough), and useful is even more important. OpenAPIs provide much more than documentation for an API. They provide all the technical details an API consumer will need to successfully work with an API.

While there are obvious payoffs for having an OpenAPI, like being able to publish documentation, and generate code libraries. There are many other uses for an OpenAPI like loading into [Postman](https://www.getpostman.com/), [Stoplight](https://stoplight.io/), and many other API services and tooling that helps developers understand what an API does, and reduce friction when they integrate, and have to maintain their applications. Having an OpenAPI available is becoming a default mode of operation, and something every API provider should have.
