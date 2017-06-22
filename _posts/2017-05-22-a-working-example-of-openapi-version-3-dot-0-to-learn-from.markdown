---
title: A Working Example Of OpenAPI Version 3.0 To Learn From
date: 2017-05-22 12:00:00 Z
tags:
- Definitions
- OpenAPI
image: https://s3.amazonaws.com/kinlane-productions/mermade/mermade-swagger2openapi-logo.png
---

<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/mermade/mermade-swagger2openapi-logo.png" align="right" width="40%" /></p>I learn almost everything I know by reverse engineering what I come across doing my monitoring of the API space. I feel it is important for leaders in the API space to share a significant portion of our work publicly, and tell the story behind our work so that others can learn from us. Whether folks realize it or not, this is why much of the wider API community works as it does, and has accumulated much of the forward motion we all enjoy today.

I have been getting a lot of questions lately regarding tooling for version 3.0 of the OpenAPI specification. I'm working to evolve [my OpenAPI toolbox](http://openapi.toolbox.apievangelist.com/), and populate with any services or tools I come across that support version 3.0. I have also been getting requests from folks about if I know where there are any working examples of OpenAPI definitions in the version 3.0 format. So I reached out to my friend Mike Ralphson ([@PermittedSoc](https://twitter.com/PermittedSoc)), who is doing interesting work when it comes to OpenAPI and GraphQL, and he responded with a working example for us of moving from version 2.0 to 3.0 of the OpenAPI spec. 

[He took the version 2.0 from the Authentiq Connect API](https://raw.githubusercontent.com/AuthentiqID/authentiq-docs/master/docs/swagger/provider.yaml):

<script src="https://gist.github.com/kinlane/23df6a0f26b0e455d4eae265f47d8d77.js"></script>

[Then he converted it to version 3.0](https://github.com/Mermade/swagger2openapi/blob/master/schemas/openapi-3.json):

<script src="https://gist.github.com/kinlane/d2a3d905eae9fb60a52dd0e14b78412a.js"></script>

Mike accomplished all of this with [his OpenAPI 2.0 to 3.0 converter and validator that he has published to Github](https://github.com/mermade/swagger2openapi). His Github organization is always full of interesting work, I recommend staying in tune with whatever he is committing.

Thanks for sharing Mike! Hopefully, it provides a reference for folks seeking a working example of OpenAPI 3.0 out in the wild. I'll be keeping an eye out for additional version 3.0 OpenAPI examples, as well as any other tooling like [swagger2openapi](https://github.com/mermade/swagger2openapi) that I can add to the [toolbox](http://openapi.toolbox.apievangelist.com/). 