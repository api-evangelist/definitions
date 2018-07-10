---
published: true
layout: post
title: Using OpenAPI And JSON PATCH To Articulate Changes For Your API Road Map
date: 2018-07-10T09:00:00.000Z
tags:
  - API Evangelist
  - Road Map
  - Definitions
  - Versioning
  - Change Log
  - Issues
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/downtheline_dali_three.jpg
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>I'm doing a lot of thinking regarding how JSON PATCH can be applied because of my work with [Streamdata.io](http://streamdata.io). When you proxy an existing JSON API with Streamdata.io, after the initial response, every update sent over the wire is articulated as a [JSON PATCH](https://tools.ietf.org/html/rfc6902) update, showing only what has changed. It is an efficient, and useful way to show what has changed with any JSON API response, while being very efficient about what you transmit with each API response, reducing polling, and taking advantage of HTTP caching.

As I'm writing an OpenAPI diff solution, helping understand the differences between OpenAPI definitions I'm importing, and allowing me to understand what has changed over time, I can't help but think that JSON PATCH would be a great way to articulate change of the surface area of an API over time--that is, if everyone loyally used OpenAPI as their API contract. Providing an OpenAPI diff using JSON PATCH would be a great way to articulate an API road map, and tooling could be developed around it to help API providers publish their road map to their portal, and push out communications with API consumers. Helping everyone understand exactly what is changing in way that could be integrated into existing services, tooling, and systems--making change management a more real time, "pipelinable" (making this word up) affair.

I feel like this could help API providers better understand and articulate what might be breaking changes. There could be tooling and services that help quantify the scope of changes during the road map planning process, and teams could submit OpenAPI definitions before they ever get to work writing code, helping them better see how changes to the API contract will impact the road map. Then the same tooling and services could be used to articulate the road map to consumers, as the road map becomes approved, developed, and ultimately rolled out. With each OpenAPI JSON PATCH moving from road map to change log, keeping all stakeholders up to speed on what is happening across all API resources they depend on--documenting everything along the way.

I am going to think more about this as I evolve my open API lifecycle. How I can iterate a version of my OpenAPI definitions, evaluate the difference, and articulate each update using JSON PATCH. Since more of my API lifecycle is machine readable, I'm guessing I'm going to be able to use this approach beyond just the surface area of my API. I'm going to be able to use it to articulate the changes in my API pricing and plans, as well as licensing, terms of service, and other evolving elements of my operations. It is a concept that will take some serious simmering on the back burners of my platform, but a concept I haven't been able to shake. So I might as well craft some stories about the approach, and see what I can move forward as I continue to define, design, and iterate on the APIs that drive my platform and API research forward.
