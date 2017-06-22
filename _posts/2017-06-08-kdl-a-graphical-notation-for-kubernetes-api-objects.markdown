---
title: 'KDL: A Graphical Notation for Kubernetes API Objects'
date: 2017-06-08 14:00:00 Z
tags:
- Containers
- Definitions
- API Evangelist
image: https://s3.amazonaws.com/kinlane-productions/openshift/kubernetes-kdl-deploy-image19-24.png
---

<p><a href="https://blog.openshift.com/kdl-notation-kubernetes-app-deploy/"><img src="https://s3.amazonaws.com/kinlane-productions/openshift/kubernetes-kdl-deploy-image19-24.png" align="right" width="40%" style="padding: 15px;" /></a></p>[I am learning about the Kubernetes Deployment Language (KDL) today](https://blog.openshift.com/kdl-notation-kubernetes-app-deploy/), trying to understand their approach to defining their notion of Kubernetes API objects. It feels like an interesting evolution in how we define our infrastructure, and begin standardizing the API layer for it so that we can orchestrate as we need.

They are standardizing the Kubernetes API objects into the following buckets:

Cluster - The orchestration level of things.
Compute - The individual compute level.
Networking - The networking layer of it all.
Storage - Storage behind our APIs.

This has elements of [my API lifecycle research](http://dev.apievangelist.com/api-lifecycle/), as well as a containerized, clustered, BaaS 2.0 in my view. Standardizing how we define and describe the essential layers of our API and application infrastructure. I could also see standardizing the testing, monitoring, performance, security, and other critical aspects of doing this at scale.

I'm also fascinated at how fast YAML has become the default orchestration template language for folks in the cloud containerization space. I'll add KDL to my [API definition](http://definitions.apievangelist.com) and [container research](http://containers.apievangelist.com) and keep an eye on what they are up to, and keep an eye out for other approaches to standardizing the API layer for deploying, managing, and scaling our increasingly containerized API infrastructure.