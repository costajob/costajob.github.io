---
layout:     post
title:      "Freedomless"
date:       2019-10-22 09:41:33 +0200
categories: thoughts
---

It was 2003 when I first heard about *the cloud*. At that time I worked for a small web agency, where we are used to host applications on our own servers and automation was a vague word.

Google had just started offering its search algorithm, appearing as a *powered-by* logo behind the Yahoo one. Few socials exist at that time and video streaming do require a flash plugin or, if you were unfortunate, a Java applet.   

The rest is history.

Today it's rare your application is hosted on a physical server, more probably it runs within a container that will be destroyed upon the HTTP response. Data flows in gigabytes per second, persisted forever somewhere. 

Serverless is becoming mainstream. Gone are the days when developers have to worry about security, scalability and communication layers: just wrap a fragment of your logic within a function and drop it in the cloud.

Artificial intelligence can be plugged into your system by the ease of a click, no worries about the data on which these models are trained, they already have them (haven't you agreed?).

The (broken) promise is to reduce costs by using only the resources you need, you can easily monitor your money flow on dedicated dashboards. No worries if price policies change at a constant pace (AutoML anyone?), at the end you can always contact your vendor asking for a discount, threatening to switch otherwise.

In this respect, what about migrating from one cloud platform to another?  

Well, if you have separated your business logic from your deployment model it *should* be easy.  The hard part is recognizing the business logic from all of the rest: looking at project codebase you can immediately spot which cloud vendor the application is coupled with, barely you can tell what it does.

Chances are that your system will end up living within a multi-cloud environment, with each service coupled to a different vendor. Do not despair, you can opt for one of the multi-cloud-orchestrator tools out there and let it supervise the mess.

Everything is available, scalable and tangled to the cloud.  

Just relax on the seat and let the auto-pilot drive you back home: no traffic jam, no incidents, no thrills, no freedom.
