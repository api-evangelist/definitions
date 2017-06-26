---
title: The Open Service Broker API
date: 2017-06-27 13:00:00 Z
tags:
- Definitions
- Plugin
- Discovery
- Definitions
- API Evangelist
image: https://s3.amazonaws.com/kinlane-productions/open-service-broker-api/osbapi_logo_concept3_wtm.png
---

<p><a href="https://openservicebrokerapi.org/"><img src="https://s3.amazonaws.com/kinlane-productions/open-service-broker-api/osbapi_logo_concept3_wtm.png" align="right" width="40%" style="padding: 20px;" /></a></p>Jerome Louvel [from Restlet](http://apis.how/5ytnitnakm) introduced me to [the Open Service Broker API](https://openservicebrokerapi.org/) the other day, a "project allows developers, ISVs, and SaaS vendors a single, simple, and elegant way to deliver services to applications running within cloud-native platforms such as Cloud Foundry, OpenShift, and Kubernetes. The project includes individuals from Fujitsu, Google, IBM, Pivotal, RedHat and SAP."

Honestly, I only have so much cognitive capacity to understand everything I come across, so I pasted the link into my super secret Slack group for API super heroes to get additional opinions. My friend James Higginbotham ([@launchany](https://twitter.com/launchany)) quickly responded with, "if I understand correctly, this is a standard that would be equiv to Heroku's Add-On API? Or am I misunderstanding? The Open Service Broker API is a clean abstraction that allows ‘services’ to expose a catalog of capabilities, as well as the ability to create, use and delete those services. Sounds like add-on support to me, but I could be wrong[...]But seems very much like vendor-to-vendor. Will be interesting to track."

At first glance, I thought it was more of an aggregation and/or discovery solution, but I think James is right. It is an API scaffolding that SaaS platforms can plug into their platforms to broker other 3rd party API services. It allows any platform to offer [an environment for extending your platform like Heroku does](https://devcenter.heroku.com/categories/extending-heroku), as James points out. It is something that adds an API discovery dimension to the concept of offering up plugins, or I guess what could be an embedded API marketplace within your platform. Opening up [wholesale](http://apievangelist.com/2014/01/30/what-will-it-take-to-sell-my-api-as-a-wholesale-resource/) and private label opportunities for API providers to sell their warez directly on other people's platforms.

The concept really isn't anything new. I remember developing document print plugins for Box back when I worked with the Mimeo print API in 2011. [The Open Service Broker API](https://openservicebrokerapi.org/) is just looking to standardize this approach so hat  API provider could bake in a set of 3rd party partner APIs directly into their platform. [I've recently added a plugin area to my API research](http://plugin.apievangelist.com/). I will add the Open Service Broker API as an organization within this research. I'm probably also going to add it to my [API discovery research](http://discovery.apievangelist.com/), and I'm even considering expanding it into an API marketplace section of my research.  I can see add-on, plugin, marketplace, and [API brokering like this grow into its own discipline](http://apievangelist.com/2014/10/10/exploring-the-possibilities-of-being-an-api-broker/), with a growing number of definitions, services, and tools to support.
