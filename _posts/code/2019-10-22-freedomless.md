---
layout:     post
title:      "Freedomless"
date:       2019-10-22 09:41:33 +0200
categories: code
---

It was 2004 that I first heard about the first cloud service. At that time I worked for a small web agency, where we are used to host applications on our own servers (automation was a vague word).

Google has just recently started offering its search algorithm, initially appearing as a powered-by logo behind the Yahoo one. Few socials exist at that time (MySpace) and video streaming do require a flash plugin or, if you were unfortunate, a Java applet.  The rest is history.

Today it's rare your site is hosted by a physical server, more probably it runs within a container that will be destroyed upon HTTP response consumption. Data flows in gigabytes per second, persisted forever in the cloud. 

Serverless is becoming mainstream, promising small infrastructure costs and offering macro-blocks architectural patterns. Developers can forgive about security, persistence, scalability, communication layers: all is already there, just wrap a fragment of your business logic within a function and drop it in the cloud.

Artificial intelligence can be plugged into your system by the ease of a click, no worries about the data on which these models are trained, they already have them. Haven't you already agreed?

Everything is available, scalable and tangled to the cloud.

What about migrating from one cloud service to another? Well, if you have separated your business logic from your deployment model it "should" be easy.  
The hard part is recognizing business logic from all of the rest: looking at a project's codebase you can immediately understand which cloud service an application is coupled with, barely you can tell what the it does.

The freedom to introduce new solutions later in the application lifecycle and control external dependencies footprint are all gone. If you are lucky enough a new version of the cloud APIs will suit your problems, after all, they know better than you how things get done.

It feels like letting the auto pilot drive you back home, while relaxing on the seat: no traffic jam, no incidents, no thrills, no freedom.
