---
title: Keen IO Pushing Forward The Data Schema Conversation
date: 2017-05-22 15:00:00 Z
tags:
- Definitions
- Schema
- Analysis
image: https://s3.amazonaws.com/kinlane-productions/keen/1-6YVuTRnIIEM7o6XQO-QtMA.png
---

<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/keen/1-6YVuTRnIIEM7o6XQO-QtMA.png" align="right" width="405" /></p>[I wrote earlier this year that I would like us all to focus more on our schema and definitions of our data we use across API operations](http://apievangelist.com/2017/01/19/focusing-on-common-api-definitions-schema-scopes-and-specifications/). Since then I've been keeping an eye out for any other interesting signs in this area [like Postman with their data editor](http://apievangelist.com/2017/03/15/getting-our-schema-in-order-with-postmans-new-data-editor/), and now I've come across [the Streams Manager for inspecting the data schema of your event collections in Keen IO.](https://blog.keen.io/a-new-way-to-debug-your-data-models-b7bc49ccf97a).

With Streams Manager you can:

* Inspect and review the data schema for each of your event collections
* Review the last 10 events for each of your event collections
* Delete event collections that are no longer needed
* Inspect the trends across your combined data streams over the last 30-day period

Keen IO provides us with an interesting approach to getting in tune with the schema across your event collections. I'd like to see more of this across the API lifecycle. I understand that companies like Runscope, Stoplight, Postman, and others already let us peek inside of each API call, which includes a look at the schema in play. This is good, but I'd like to see more schema management solutions at this layer helping API providers from design to deprecation.

In 2017 we all have an insane amount of bits and bytes flowing around us in our daily business operations. APIs are only enabling this to grow, opening up access to our bits to our partners and on the open web. We need more solutions like [Keen's Stream Manager](https://blog.keen.io/a-new-way-to-debug-your-data-models-b7bc49ccf97a), but for every layer of the API stack, allowing us to get our schema house in order, and make sense of the growing data bits we are producing, managing, and sharing. 