---
title: API Environment Portability
date: 2017-06-27 13:00:00 Z
tags:
- Client
- Testing
- Monitoring
- Environment
- Definitions
- API Evangelist
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/runscope/1-runscope-env.jpg
---

<p><a href="https://blog.runscope.com/posts/tutorial-copying-runscope-environments-using-runscope-api"><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/runscope/1-runscope-env.jpg" align="right" width="40%" style="padding: 15px;" /></a></p>I was reading [the post from Runscope on copying environments using their new API](https://blog.runscope.com/posts/tutorial-copying-runscope-environments-using-runscope-api). I was looking through the request and response structure for their API, it looks like a pretty good start when it comes to what I'd call API environment portability. I'm talking about allowing us to define, share, replicate, and reuse the definitions for our API environments across the services and tools we are depending on.

If our API environment definitions shared a common schema, [and API like Runscope provides](https://www.runscope.com/docs/api/environments), I could take my Runscope environment settings, and use them in my Stoplight, [Restlet Client](https://restlet.com/modules/client/), Postman, and other API services and tooling. It would also help me templatize and standardize my development, staging, production, and other environments across the services I use. Assisting me in keeping my environment house in order, and also something that I can use to audit and turn over my environments to help out with security.

It is just a thought. An API environment API, possessing an evolving but common schema just seems like one of those things that would make the entire API space work a little smoother. Making our API environments exportable, importable, and portable just seems like it would help us think through when it comes setting up, configuring, managing, and evolving our API environments--who knows maybe someday we'll have API service providers who help us manage our API environments, dictating how they are used across the growing number of API services we are depending on.

**Disclosure:** Runscope and Restlet are API Evangelist partners.
