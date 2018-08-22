---
published: true
layout: post
title: Searching For APIs That Possess Relevant Company Information
date: 2018-08-22T09:00:00.000Z
tags:
  - API Evangelist
  - Discovery
  - Search
  - Definitions
image: >-
  https://s3.amazonaws.com/kinlane-productions/algo-rotoscope/stories-new/cityscape_copper_circuit.jpg
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>I'm evolving [the search for the Streamdata.io API Gallery](http://api.gallery.streamdata.io/) I've been working on lately. I'm looking to move the basic keywords search that searches the API name and description, as well as the API path, summary, and description using a key word or phrase, to also be about searching parameters in a meaningful way. Each of the APIs in the Streamdata.io API have an OpenAPI definition. It is how I render each of the individual API paths using Jekyll and Github Pages. These parameters give me another dimension of data in which I can index, and use as a facet in my API gallery search.

I am developing different sets of vocabulary to help me search against the parameters used across APIs, with one of them being focused on company related information. I'm trying to find APIs that provide the ability to add, update, and search against company related data, content, and execute algorithms that help make sense of company resources. There is no perfect way to search for API parameters that touch on company resources, but right now I'm looking for a handful of fields: _company, organization, business, enterprise, agency, ticker, corporate, and employer_. Returning APIs that have a parameter with any of those words in the path or summary, and weighting differently if it is in the description or tags for each API path.

Next, I'm also tagging each API path that has a URL field, because this will allow me to connect the dot to a company, organization, or other entity via the domain. This is all I'm trying to do, is connect the dots using the parameter structure of an API. I find that there is an important story being told at the API design layer, and API search and discovery is how we are going to bring this story out. Connecting the dots at the corporate level is just one of many interesting stories out there, just waiting to be told. Pushing forward the conversation around how we understand the corporate digital landscape, and what resources they have available.

[You can do a basic API search at the bottom of the Streamdata.io API Gallery main page](http://api.gallery.streamdata.io/). I do not have my parameter search available publicly yet. I want to spend more time refining my vocabularies, and also look at searching the request and response bodies for each path--I'm guessing this won't be as straightforward, as parameters has been. Right now I'm immersed in understanding the words we use to design our APIs, and craft our API documentation. It is fascinating to see how people describe their resources, and how they think (or don't think) about making these resources available to other people. OpenAPI definitions provide a fascinating way to look at how APIs are opening up access to company information, establishing the digital vocabulary for how we exchange data and content, and apply algorithms to help us better understand the business world around us.
