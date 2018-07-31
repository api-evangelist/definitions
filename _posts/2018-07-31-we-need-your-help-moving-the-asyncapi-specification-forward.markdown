---
published: true
layout: post
title: We Need Your Help Moving The AsyncAPI Specification Forward
date: 2018-07-31T09:00:00.000Z
tags:
  - API Evangelist
  - AsyncAPI
  - Event-Driven
  - Event-Architecture
  - Real Time
  - Definitions
image: >-
  https://s3.amazonaws.com/kinlane-productions/asyncapi/asyncapi-define-your-message-driven-apis.png
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>We need your help moving [the AsyncAPI specification](https://www.asyncapi.com/) forward. Ok, first, [what is the AsyncAPI specification](https://github.com/asyncapi/asyncapi)? "The AsyncAPI Specification is a project used to describe and document Asynchronous APIs. The AsyncAPI Specification defines a set of files required to describe such an API. These files can then be used to create utilities, such as documentation, integration and/or testing tools." AsyncAPI is a sister specification [to OpenAPI](https://www.openapis.org/), but instead of describing the request and response HTTP API landscape, AsyncAPI is describing the message, topic, event, and streaming API landscape across the HTTP and TCP landscape. It is how we are going to continue to ensure there is machine readable descriptions of this portion of the API landscape, for use in tooling and services.

My friend Fran Mendez (@fmvilas) is the creator and maintainer of the specification, and he is doing way too much of the work on this important specification and he needs our help. Here is Fran's request for our help to contribute:

> _AsyncAPI is an open source project that's currently maintained by me, with no company or funds behind. More and more companies are using AsyncAPI and the work needed is becoming too much work for a single person working in his spare time. E.g., for each release of the specification, tooling and documentation should be updated. One could argue that I should be dedicating full time to the project, but it's in this point where it's too much for spare time and very little to get enough money to live. I want to keep everything for free, because I firmly believe that engineering must be democratized. Also, don't get me wrong, this is not a complaint. I'm going to continue running the project either with or without contributors, because I love it. This is just a call-out to you, the AsyncAPI lover. I'd be very grateful if you could lend a hand, or even raise your hand and become a co-maintainer. Up to you 😊_

> _On the other hand, I only have good words for all of you who use and/or contribute to the project. Without you, it would be just another crazy idea from another crazy developer 😄_

> _Thank you very much! 🙌_

> _– Fran Mendez_

When it comes to contributing to the AsyncAPI, [Fran has laid out some pretty clear ways in which he needs our help](https://github.com/asyncapi/contribute/blob/master/README.md), providing a range of options for you to pitch in and help, depending on what your skills are, and the bandwidth you have in your day.

**1. The specification**
There is always work to do in the spec. It goes from fixing typos to writing and reviewing new proposals. I try to keep releases small, to give time to tooling authors to update their software. If you want to start contributing, take a look at https://github.com/asyncapi/asyncapi/issues, pick one, and start working on it. It's always a good idea to leave a comment in the issue saying that you're going to work on it, just so other people know about it.

**2. Tooling**
As developers, this is sometimes the most straightforward way to contribute. Adding features to the existing tools or creating new ones if needed. Examples of tools are:

- Code generators (multiple languages):
	- https://github.com/asyncapi/generator
	- https://github.com/asyncapi/node-codegen (going to be deprecated soon in favor of https://github.com/asyncapi/generator)
- Documentation generators (multiple formats):
	- https://github.com/asyncapi/generator
	- https://github.com/asyncapi/docgen (going to be deprecated soon in favor of https://github.com/asyncapi/generator)
	- https://github.com/Mermade/widdershins
	- https://github.com/asyncapi/asyncapi-node
	- https://github.com/asyncapi/editor
- Validation CLI tool (nobody implemented it yet)
- API mocking (nobody implemented it yet)
- API gateways (nobody implemented it yet)

As always, usually the best way to contribute is to pick an issue and chat about it before you create a pull request.

**3. Evangelizing**
Sometimes the best way to help a project like AsyncAPI is to simply talk about it. It can be inside your company, in a technology meetup or speaking at a conference. I'll be happy to help with whatever material you need to create or with arguments to convince your colleagues that using AsyncAPI is a good idea 😊

**4. Documentation**
Oh! documentation! We're trying to convince people that documenting your message-driven APIs is a good idea, but we lack documentation, especially in tooling. This is often a task nobody wants to do, but the best way to get great knowledge about a technology is to write documentation about it. It doesn't need to be rewriting the whole documentation from scratch, but just identifying the questions you had when started using it and document them.

**5. Tutorials**
We learn by examples. It's a fact. Write tutorials on how to use AsyncAPI in your blog, Medium, etc. As always, count on me if you need ideas or help while writing or reviewing.

**6. Stories**
You have a blog and write about the technology you use? Writing about success stories, how-to's, etc., really helps people to find the project and decide whether they should bet on AsyncAPI or not.

**7. Podcasts/Videos**
You have a Youtube channel or your own podcast? Talk about AsyncAPI. Tutorials, interviews, informal chats, discussions, panels, etc. I'll be happy to help with any material you need or finding the right person for your interview.

<p><img src="https://s3.amazonaws.com/kinlane-productions/asyncapi/asyncapi-example-streetlight.png" width="45%" align="right" style="padding: 15px;" /></p>I'm going to take the liberty and add an 8th option, because I'm so straightforward when it comes to this game, and I know where Fran needs help.

**8. Money $$$$**
AsyncAPI needs investment to help push forward, allowing Fran to carve out time, work on tooling, and pay for travel expenses when it comes to attending events and getting the word out about what it does. There is no legal entity setup for AsyncAPI, but I'm sure with the right partner(s) behind it, we can make something happen. Step up.

AsyncAPI is important. We all need to jump in and help. I've been investing as many cycles as I can in helping learn about the specification, and tell stories about why it is important. I've been working hard to learn more about it so I can contribute to the roadmap. I'm using it as one of the key definition formats driving [my Streamdata.io API Gallery work](http://api.gallery.streamdata.io/), which is all driven using APIs.json, OpenAPI, and provides Postman Collections as well as AsyncAPI definitions when a message, topic, event, or streaming API is present. AsyncAPI is where OpenAPI (Swagger) was in 2011/2012, and with more investment, and a couple more years of adoption and maturing, it will be just as important for working with the evolving API landscape as OpenAPI and Postman Collections are.

If you want to get involved with AsyncAPI, feel free to reach out to me. I'm happy to help you get up to speed on why it is so important. I'm happy to help you understand how it can be applied, and where it fits in with your API infrastructure. You are also welcome to just dive in, as [Fran has done an amazing job of making sure everything is available in the Github organization for the project](https://github.com/asyncapi/), where you can submit pull requests, and issues regarding whatever you are working on and contributing. Thanks for your help in making AsyncAPI evolve, and something that will continue to help us understand, quantify, and communicate about the diverse API landscape.
