---
published: true
layout: post
title: Constraints Introduced By Supporting Standardized API Definitions and Schema
date: 2018-05-08T09:00:00.000Z
tags:
  - API Evangelist
  - Design
  - Definitions
  - Standards
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/server-cloud1_feed_people.jpg
---
I've had a few API groups contact me lately regarding the challenges they are facing when it comes to supporting organizational, or industry-wide API definitions and schema. They were eager to support common definitions and schema that have been standardized, but were getting frustrated by not being able to do everything they wanted, and having to live within the constraints introduced by the standardized definitions. Which is something that doesn't get much discussion by those of use who are advocating for standardization of APIs and schema.

**Web APIs Come With Their Own Constraints**<br />
We all want more developers to use our APIs. However, with more usage, comes more responsibility. Also, to get more usage our APIs need to speak to a wider audience, something that common API definitions and schema will help with. This is why web APIs are working, because they speak to a wider audience, however with this architectural decision we are making some tradeoffs, and accepting some constraints in how we do our APIs. This is why REST is just one tool in our toolbox, so we can use the right tool, establish the right set of constraints, to allow our APIs to be successful. The wider our API toolbox, the wider the number options we will have available when it comes to how we design our APIs, and what schema we can employ

**Allowing For Content Negotiation By Consumers**<br />
One way I've encouraged folks to help alleviate some of the pain around the adoption of common API definitions and schema is to provide content negotiation to consumers, allowing them to obtain the response they are looking for. If people want the standardized approaches they can choose those, and if they want something more precise, or custom they can choose that. This also allows API providers to work around the API standards that have become bottlenecks, while still supporting them where they matter. Having the best of both worlds, where you are supporting the common approach, but still able to do what you want when you feel it is important. Allowing for experimentation as well as standardization using the same APIs.

**Participate In Standards Body and Process**<br />
Another way to help move things forward is to participate in the standards body that is moving an API definition or schema forward. Make sure you have a seat at the table so that you can present your case for where the problems are, and how to improve on the design, definition, and schema being evolved. Taking a lead in creating the world you want to see when it comes to API and schema standards, and not just sitting back being frustrated because it doesn't do what you want it to do. Having a role in the standards body, and actively participating in the process isn't easy, and it can be time consuming, but it can be worth it down the road and helping you better achieve your goals when it comes to your APIs operating as you aspect, as well as the wider community and industry you are serving.

Delivering APIs at scale won't be easy. To reach a wide audience with your API it helps to be speaking a common vocabulary. This doesn't always allow you to move as fast as you'd like, and do everything exactly as you envision. You will have to compromise. Operate within constraints. However, it can be worth it. Not just for your organization, but for the overall health of your community, and the industry you operate in. You never know, with a little patience, collaboration, and communication, you might learn even new approaches to defining your APIs and schema that you didn't think about in isolation. Also, experimentation with new patterns will still be important, even while working to standardize things. In the end, a balance between standardized and custom will make the most sense, and hopefully alleviate your frustrations in moving things forward.
