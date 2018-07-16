---
published: true
layout: post
title: TVMaze Uses HAL For Their API Media Type
date: 2018-07-16T09:00:00.000Z
tags:
  - API Evangelist
  - Hypermedia
  - Design
  - Definitions
image: 'https://s3.amazonaws.com/kinlane-productions/tv-maze/tvm_api.png'
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>One of the layers of the API universe where I come across an increased number Hypermedia APIs is in the movie, television, and entertainment space. Where having a more flowing API experience makes a lot of sense, and the extra investment in link relations will pay off. One example of this I recently came across was over at TVMaze, [who has a pretty robust hypermedia API](https://www.tvmaze.com/api), where they opted for using HAL as their media type.

Like any good hypermedia should, TVMaze begins with its root URL: http://api.tvmaze.com, and provides a robust set of endpoints from there:

## <strong>Search</strong></a>
- <a href="http://www.tvmaze.com/api#show-search">Show Search</a>
- <a href="http://www.tvmaze.com/api#show-single-search">Show single search</a>
- <a href="http://www.tvmaze.com/api#show-lookup">Show Lookup</a>
- <a href="http://www.tvmaze.com/api#people-search">People search</a>

## <strong>Schedule</strong></a>
- <a href="http://www.tvmaze.com/api#full-schedule">Full Schedule</a>

## <strong>Shows</strong></a>
- <a href="http://www.tvmaze.com/api#show-main-information">Show main information</a>
- <a href="http://www.tvmaze.com/api#show-episode-list">Show episode list</a>
- <a href="http://www.tvmaze.com/api#episode-by-number">Episode by number</a>
- <a href="http://www.tvmaze.com/api#episodes-by-date">Episodes by date</a>
- <a href="http://www.tvmaze.com/api#show-seasons">Show seasons</a>
- <a href="http://www.tvmaze.com/api#season-episodes">Season episodes</a>               
- <a href="http://www.tvmaze.com/api#show-cast">Show cast</a>
- <a href="http://www.tvmaze.com/api#show-crew">Show crew</a>
- <a href="http://www.tvmaze.com/api#show-aka">Show AKA's</a>
- <a href="http://www.tvmaze.com/api#show-index">Show index</a>

## <strong>People</strong></a>
- <a href="http://www.tvmaze.com/api#person-main-information">Person main information</a>
- <a href="http://www.tvmaze.com/api#person-cast-credits">Person cast credits</a>
- <a href="http://www.tvmaze.com/api#person-crew-credits">Person crew credits</a>

## <strong>Updates</strong></a>
- <a href="http://www.tvmaze.com/api#show-updates">Show updates</a>

The TVMaze API isn't an overly complex hypermedia API. I think it is simple, elegant, and shows how you can use link relations to establish a more meaningful experience for API consumers. Allowing you to navigate the large, ever-changing catalog of television shows, allowing the API client to do the heavy lifting of navigating the shows, schedules, and people involved with each production.

There hasn't been enough showcasing of the [hypermedia APIs](http://hypermedia.apievangelist.com) available out there. Usually once a year I remember to give the subject some attention, or when I come across interesting ones like TVMaze. Hypermedia isn't just an academic idea anymore, and is something that has gotten traction in a number of sectors, and I keep seeing signs of growth and adoption. I don't think it will be the API solution most hypermedia believers envisioned it, but I do think it is a viable tool in our API toolbox, and for the right projects it makes a lot of sense.