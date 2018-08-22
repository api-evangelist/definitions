---
published: true
layout: post
title: It Is Hard To Go API Define First
date: 2018-08-22T09:00:00.000Z
tags:
  - API Evangelist
  - Definitions
  - Design
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories-new/69_120_800_500_0_max_0_1_-1.jpg
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>Last year I started saying API define first, instead of API design first. In response to many of the conversations out there about designing, then mocking, and eventually deploying your APIs into a production environment. I agree that you should design and iterate before writing code, but I feel like we should be defining our APIs even before we get to the API design phase. Without the proper definitions on the table, our design phase is going to be a lot more deficient in standards, common patterns, goals, and objectives, making it important to invest some energy in defining what is happening first--then iterate on the API definitions throughout the API lifecycle, not just design.

I prefer to have a handful of API definitions drafted, before I move onto to the API design phase:

- **Title** - A simple, concise title for my API.
- **Description** - A simple, concise description for my API.
- **JSON Schema** - A set of JSON schema for my APIs
- **OpenAPI** - An OpenAPI for the surface area of my API.
- **Assertions** - A list of what my API should be delivering.
- **Standards** - What standards are being applied with this API.
- **Patterns** - What common web patterns will be used with this API.
- **Goals** - What are the goals for this particular API.

I like having all of this in a GitHub repository before I get to work, actually designing my APIs. It provides me with the base set of definitions I need to go to be as effective as I can in my API design phase. Of course, each of these definitions will be iterated, added to, and evolved as part of the API design phase, and beyond. The goal is to just get a base set of building blocks on the workbench, properly setting the tone for what my API will be doing. Grounding my API work early on in the API lifecycle, in a consistent way that I can apply across many different APIs.

The problem with all of this, is that it is easier said than done. I still like to hand code my APIs. It is something I've been doing for 20 years, and it is a habit that is hard to kick. When designing an API, often times I do not know what is possible, and I need to hack on the solution for a while. I need to hack on and massage some data, content, or push forward my algorithm a little. All of this has to happen before I can articulate the interface will look like. Sure, I might have some basic RESTful notions about what API paths will be, and the schema I've gathered will drive some of the conversation, but I still need to hack together a little goodness, before I can design.

This is ok. With some APIs I will be able to define and then design without ever touching any code. While others I will still have to prototype at least a function to prove the concept behind the API. Once I have the proof of concept, then I can start crafting a sensible interface using OpenAPI, then mock, and work with the concept a little more within an API design phase. Ultimately, I do not think there is any RIGHT WAY to develop an API. I think there are healthier, and less healthier ways. I think there are more hardened, and proven ways, but I also think there should be experimental, and even legacy ways of doing things. My goal is to always make sure the process is as sensible and pragmatic as it can be, while meeting the immediate, and long term business goals of my company, as well as my partners.
