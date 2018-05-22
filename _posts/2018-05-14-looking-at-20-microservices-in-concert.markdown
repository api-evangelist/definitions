---
published: true
layout: post
title: Looking At 20 Microservices In Concert
date: 2018-05-14T09:00:00.000Z
tags:
  - API Evangelist
  - Microservices
  - Definitions
  - Github
  - Design
  - Lifecycle
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories/losangeles-from-observatory_free_woman.jpg
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>I checked out the Github repositories for twenty microservices of one of my clients recently, looking understand what is being accomplished across all these services as they work independently to accomplish a single collective objective. I'm being contracted with to help come in blindly and provide feedback on the design of the APIs being exposed across services, and help provide guidance on their API lifecycle, as well as eventually API governance when things have matured to that level. Right now we are addressing pretty fundamental definition and design issues, but eventually we'll hopefully graduate to the next level.

[A complete and up to date README for each microservice is essential to understanding what is going on with a service](http://apievangelist.com/2018/04/30/a-readme-for-your-microservice-github-repository/), and a robust OpenAPI definition is critical to breaking down the details of what each API delivers. When you aren't part of each service's development team it can be difficult to understand what each service does, but with an up to date README and OpenAPI, you can get up to speed pretty quickly. If an service is well documented via its README, and the API is well designed, and the surface area is reflected in it's OpenAPI, you can go from not knowing what a service does to, understanding its value within hopefully minutes, not hours.

When each service possesses an OpenAPI it becomes possible to evaluate what they deliver at scale. You can take all APIs, their paths, headers, parameters, and schema and out them in different ways so that you can begin to paint a picture of what they deliver in aggregate. Bringing all the disparate services back together to perform together in a sort of monolith concert, while still acknowledging they all do their own thing independently. Allowing us to look at how many different service can be used in concert to deliver a single application, or potentially a variety of application instances. Thinking critically about each independent service, but more importantly how they all work together.

I feel like many groups are still struggling with decomposing their monolithic systems into separate services, and while some are doing so in a domain-driven way, few are beginning to invest in understanding how they move forward with services in concert to deliver on application needs. Many of the groups I'm working with are so focused on decomposing and tearing down, they aren't thinking too critically about how they will make all of this begin work together again. I see monolith systems working like a massive church organ which take a lot of maintenance, and require a single (or handful) of knowledgeable operators to play. Where microservices are much more like an orchestra, where every individual player has a role, but they play in concert, directed by a conductor. I feel like most groups I'm talking with are just beginning the process of hiring a conductor, and have a bunch of musicians roaming around--not quite ready to play any significant productions quite yet.
