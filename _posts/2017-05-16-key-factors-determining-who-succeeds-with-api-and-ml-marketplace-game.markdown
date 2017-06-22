---
title: Key Factors Determining Who Succeeds In The API and ML Marketplace Game
date: 2017-05-16 17:00:00 Z
tags:
- Definitions
- Marketplace
- Machine Learning
- Monetization
- Plans
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-marketplace.png
---

<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-marketplace.png" align="right" width="35" /></p>
I was having a discussion with an investor today about the potential of algorithmic-centered API marketplaces. I'm not talking about API marketplaces like Mashape, I'm more talking about ML API marketplaces like Algorithmia. This conversation spans multiple areas of my API lifecycle research, so I wanted to explore my thoughts on the subject some more.

I really do not get excited about API marketplaces when you think just about API discovery--how do I find an API? We need solutions in this area, but I feel good implementations will immediately move from useful to commodity, with companies like Amazon already pushing this towards a reality.

There are a handful of key factors for determining who ultimately wins the API Machine Learning (ML) marketplace game:
 
* Always Modular - Everything has to be decoupled and deliver micro value. Vendors will be tempted to build in dependency and emphasize relationships and partnerships, but the smaller and more modular will always win out.
* Easy Multi-Cloud - Whatever is available in a marketplace has to be available on all major platforms. Even if the marketplace is AWS, each unit of compute has to be transferrable to Google or Azure cloud without ANY friction.
* Enterprise Ready - The biggest failure of API marketplaces has always been being public. On-premise and private cloud API ML marketplaces will always be more successful that their public counterparts. The marketplace that caters to the enterprise will do well.
* Financial Engine - The key to markets are their financial engines. This is one area AWS is way ahead of the game, with their approach to monetizing digital bits, and their sophisticated market creating pricing calculators for estimating and predicting costs gives them a significant advantage. Whichever marketplaces allows for innovation at the financial engine level will win.
* Definition Driven - Marketplaces of the future will have to be definition driven. Everything has to have a YAML or JSON definition, from the API interface, and schema defining inputs and outputs, to the pricing, licensing, TOS, and SLA. The technology, business, and politics of the marketplace needs to be defined in a machine-readable way that can be measured, exchanged, and syndicated as needed.

Google has inroads into this realm with their [GSuite Marketplace](https://developers.google.com/apps-marketplace/), and [Play Marketplaces](https://play.google.com/store), but it feels more fragmented than [Azure](https://azuremarketplace.microsoft.com/en-us) and [AWS](https://aws.amazon.com/marketplace/) approaches. None of them are as far along as Algorithmia when it comes to specifically ML focused APIs. In coming months I will invest more time into mapping out what is available via marketplaces, trying to better understand their contents--whether application, SaaS, and data, content, or algorithmic API.

I feel like many marketplace conversations often get lost in the discovery layer. In my opinion, there are many other contributing factors beyond just finding things. [I talked about the retail and wholesale economics of Algorithmia's approach back in January](http://apievangelist.com/2017/01/03/exploring-the-economics-of-wholesale-and-retail-algorithmic-apis/), and I continue to think the economic engine will be one of the biggest factors in any API ML marketplace success--how it allows marketplace vendors to understand, experiment, and scale the revenue part of things without giving up to big of a slice of the pie.

Beyond revenue, the modularity and portability will be equally important as the financial engine, providing vital relief valves for some of the classic silo and walled garden effects we've seen the impact the success of previous marketplace efforts. I'll keep studying the approach of smaller providers like Algorithmia, as well as those of the cloud giants, and see where all of this goes. It is natural to default to AWS lead when it comes to the cloud, but I'm continually impressed with what I'm seeing out of Azure, as well as feel that Google has a significant advantage when it comes to TensorFlow, as well as their overall public API experience--we will see.