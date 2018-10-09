---
published: true
layout: post
title: A Quick Manual Way To Create An OpenAPI From A GET API Request
date: 2018-10-09T09:00:00.000Z
tags:
  - API Evangelist
  - Definitions
  - Design
  - Documentation
image: >-
  https://s3.amazonaws.com/kinlane-productions/api-definition-stories/xignite-api-url.png
---
I have numerous tools that help me create OpenAPIs from the APIs I stumble across each day. Ideally I'm crawling, scraping, harvesting, and auto-generating OpenAPIs, but inevitably the process gets a little manual. To help reduce friction in these manual processes, I try to have a variety of services, tools, and scripts I can use to make my life easier, when it comes to create a machine readable definition of an API I am using.

<p align="center"><img src="https://s3.amazonaws.com/kinlane-productions/api-definition-stories/xignite-api-url.png" width="75%" align="center"></p>

One way I'll create an OpenAPI from a simple GET API request, providing me with a machine readable definition of the surface area of that API, is using [Postman](https://www.getpostman.com/). When you have the URL copied onto your clipboard, open up your Postman, and paste the URL with all the query parameters present.

<p align="center"><img src="https://s3.amazonaws.com/kinlane-productions/api-definition-stories/postman-paste-url-in-1.png" width="75%" align="center"></p>

You'll have to save your API request, and add it to a collection, but then you can choose to share the collection, and retrieve the URL to this specific requests Postman Collection.

<p align="center"><img src="https://s3.amazonaws.com/kinlane-productions/api-definition-stories/postman-collection-share-2.png" width="75%" align="center"></p>

This gives you a machine readable definition of the surface area of this particular API, defining the host, baseURL, path, and parameters, but it doesn't give me more detail about the underlying schema being returned. To begin crafting the schema for the underlying definition of the API, and connect it to the response for my API definition, I'll need an OpenAPI--which I can create from my Postman Collection using [API Transformer from APIMATIC](https://apimatic.io/transformer).

<p align="center"><img src="https://s3.amazonaws.com/kinlane-productions/api-definition-stories/apimatic-api-transformer.png" width="75%" align="center"></p>

After pasting the URL for the Postman Collection into the API transformer form, you can generate an OpenAPI from the definition. Now you have an OpenAPI, except it is missing the underlying schema, which I will just grab the response from my last request, and convert it into JSON schema using [JSONSchema.net](https://www.jsonschema.net/). I'll just grab the properties section of these, as the bottom definitions portion of the OpenAPI specification is just JSON Schema.

<p align="center"><img src="https://s3.amazonaws.com/kinlane-productions/api-definition-stories/jsonchema-net.png" width="75%" align="center"></p>

I can merge my JSON schema with my OpenAPI, adding it to the definition collection at the bottom. With a little more love, adding a more coherent title, description, and fluffing up some of the summaries, descriptions, tags, etc., I now have a fairly robust profile of this particular API. Ideally, this is something the API provider would do, but in the absence of an OpenAPI or Postman Collection, this is a pretty quick and dirty way to produce an OpenAPI and Postman Collection from a simple GET API, but the formula works for other types of API requests as well--leaving me with a machine readable definition for an API I will be integrating with.

<p align="center"><img src="https://s3.amazonaws.com/kinlane-productions/api-definition-stories/xignite-cloud-alerts.png" width="75%" align="center"></p>

There are definitely other ways of scraping API documentation, processing .HAR files generated from a proxy, but I think this is a way that anyone, even a non-developer can accomplish. I did my version in JSON, but the same process will work for YAML, making the resulting definition a little more human readable, while still maintaining it's machine readability. I like documenting these little processes so that my readers can put to use, but it also provides a nice definition that I can use to remember how I get things done--my memory isn't what it used to be.
