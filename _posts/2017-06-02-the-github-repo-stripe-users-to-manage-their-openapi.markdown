---
title: The Github Repo Stripe Uses To Manage Their OpenAPI
date: 2017-06-02 12:00:00 Z
tags:
- Definitions
- Payments
- Github
- API Evangelist
image: https://s3.amazonaws.com/kinlane-productions/stripe/stripes-openapi-specification-on-github.png
---

I'm beating a drum every time I find a company managing their OpenAPI on Github, like we would the other code elements of our API operations. Today's drumbeat comes from my friend Nicolas Grenié ([@picsoung](https://twitter.com/picsoung)), who posted Stripe's Github repository for their OpenAPI in our Slack channel for the super cool API Evangelists in the sector. ;-)

Along with the [New York Times](http://apievangelist.com/2017/03/01/new-york-times-manages-their-openapi-using-github/), [Box](http://apievangelist.com/2017/05/22/box-goes-all-in-on-openapi/), and other API providers, [Stripe has a dedicated Github repo for managing their OpenAPI definition](https://github.com/stripe/openapi). This opens up the Stripe API for easily loading in client tools [like Restlet Client](https://restlet.com/modules/client/), and [Postman](https://www.getpostman.com/), as we as generating code samples and SDKs using services like APIMATIC. Most importantly, it allows for developers to easily understand the surface area of the Stripe API, in a way that is machine-readable, and portable.

It makes me happy to see leading API providers manage their own OpenAPI using Github like this. The API sector will be able to reach new heights when every single API provider manages their API definitions like this. I know, I know hypermedia folks--everyone should just do hypermedia. Yes, they should. However, we need some initial steps to occur before that is possible, and API providers being able to effectively communicate their API surface area to API consumers in a way that scales and can be used across the API lifecycle is an important part of this evolution. With each OpenAPI I find like this, I get more optimistic that we are getting closer to the future that RESTafarians and hypermedia folks envision--providers are doing the hard work of thinking about the definitions used in their APIs in the context of the entire API lifecycle, and the API consumers who exist along the way.