---
title: Adding Three APIMATIC OpenAPI Extensions To The OpenAPI Toolbox
date: 2017-05-31 15:00:00 Z
tags:
- SDK
- Definitions
- OpenAPI
- Extensions
image: http://kinlane-productions.s3.amazonaws.com/api_evangelist_site/blog/apimatic_dx_kits.png
---

<p><a href="https://apimatic.io/"><img src="http://kinlane-productions.s3.amazonaws.com/api_evangelist_site/blog/apimatic_dx_kits.png" align="right" width="40%" style="padding: 15px;" /></a></p>
I've added three OpenAPI extensions from [APIMATIC](https://apimatic.io/) to my [OpenAPI Toolbox](http://openapi.toolbox.apievangelist.com/), adding to the number of extensions I'm tracking on that service providers and tooling developers are using as part of their API solutions. [APIMATIC provides SDK code generation services](https://apimatic.io/), so their OpenAPI extensions are all about customizing how you deploy code as part of the integration process.

These are the three OpenAPI extensions I am adding from them:

* x-codegen-settings - These settings are globally applicable to all operations and schema definitions.
* x-operation-settings - These settings can be specified inside an &quot;operation&quot; object.
* x-additional-headers - These headers are in addition to any headers required for authentication or defined as parameters.

If you have ever used APIMATIC you know that you can do a lot more than just "SDK generation", which often has a bad reputation. APIMATIC provides some interesting ways you can use OpenAPI to dial in your SDK, script, and code generation as part of any continuous integration lifecycle.

Providing another example of how you don't have to live within the constraints of the current OpenAPI spec. Anyone can augment, and extend the current specification to meet your unique needs. Then who knows, maybe it will become useful enough, and something that might eventually be added to the core specification. Which is part of the reason I'm aggregating these specifications, and including them in [the OpenAPI Toolbox](http://openapi.toolbox.apievangelist.com/).