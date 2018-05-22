---
published: true
layout: post
title: >-
  Making the OpenAPI Contract Friendlier For Developers and Business
  Stakeholders
date: 2018-05-08T09:00:00.000Z
tags:
  - API Evangelist
  - Definitions
  - Politics of APIs
image: >-
  http://kinlane-productions.s3.amazonaws.com/algorotoscope/builder/filtered/64_98_800_500_0_max_0_1_-1.jpg
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>I was in a conference session about an API design tool today, and someone asked if you could get at the OpenAPI definition behind the solution. They said yes, but quickly also said that the definition is boring and that you don't want to be in there, you want to be in the interface. I get that service providers want you to focus on their interface, but we shouldn't be burying, or abstracting away the API contract for APIs, we should always be educating people about it, an bringing it front and center in any service, tooling, or conversation.

Technology folks burying or devaluing the OpenAPI definition with business users is common, but I also see technology folks doing it to each other. Reducing OpenAPI to be just another machine readable artifact alongside other components of delivering API infrastructure today. I think this begins with people not understanding what OpenAPI is, but I think it is sustained by people's view of what is technological magic and should remain in the hands of the wizards, and what should be accessible to a wider audience. If you limit who has access and knowledge, you can usually maintain a higher level of control, so they use your interface in the case of a vendor, or they come to you develop and build an API in the case of a developer.

There is nothing in a YAML OpenAPI definition that business users won't be able to understand. OpenAPIs aren't anymore boring than a Word document or Spreadsheet. If you are a stakeholder in the service, you should be able to read, understand, and engage with the OpenAPI contract. If we teach people to be afraid of the OpenAPI definitions we are repeating the past, and maintaining the canyon that can exist between business and IT/Developer groups. If you are in the business of burying the OpenAPI definition, I'm guessing you don't understand the portable API lifecycle potential of this API contract, and simply see it as a config, documentation, or other technical artifiact. Or you are just in the business of maintaining control and power by being the gatekeeper for the API contract, similar to how we see database people defend their domain.

Please do not devalue or hide away the OpenAPI contract. It isn't your secret sauce. It isn't boring. It isn't too technical. It is the contract for how a service will work, that will speak to business and technical groups. It is the contract that all the services and tools you will use along the API lifecycle will understand. It is fine to have the OpenAPI right behind the scenes, but always provide a button, link, or other way to quickly see the latest version, and definitely do not scare people away or devalue it when you are talking. If you are doing APIs, you should be encouraging, and investing in everyone being able to have a conversation around the API contract behind any service you are putting forward.
