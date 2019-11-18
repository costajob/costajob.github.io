---
layout:     post
title:      "Freedomless"
date:       2019-10-22 09:41:33 +0200
categories: coding
redirect_from:
  - /code/freedomless/
---

It was 2003 when I first heard about "the cloud". At that time I worked for a small web agency, where we are used to host applications on our own servers and automation was an vague word.

Google has just recently started offering its search algorithm, initially appearing as a "powered-by" logo behind the Yahoo one. Few socials exist at that time and video streaming do require a flash plugin or, if you were unfortunate, a Java applet.   

The rest is history.

Today it's rare your application is hosted on a physical server, more probably it runs within a container that will be destroyed upon HTTP response consumption. Data flows in gigabytes per second, persisted forever in the cloud. 

Serverless is becoming mainstream, promising small infrastructure costs and offering macro-blocks architectural patterns. Developers can forgive about security, scalability and communication layers: all is already there, just wrap a fragment of your business logic within a function and deploy it in the cloud.

Artificial intelligence can be plugged into your system by the ease of a click, no worries about the data on which these models are trained, they have them. Haven't you already agreed?

Everything is available, scalable and tangled to the cloud.

What about migrating from one cloud platform to another?  
Well, if you have separated your business logic from your deployment model it "should" be easy.  
The hard part is recognizing business logic from all of the rest: looking at project codebase you can immediately spot which cloud vendor the application is coupled with, but barely you can tell what it does.

The option to introduce new solutions later in the application lifecycle and control external dependencies footprint are gone.  
If you are lucky enough a new version of the cloud APIs will suit your problems, after all, they know better than you how things get done.

Just relax on the seat and let the auto-pilot drive you back home: no traffic jam, no incidents, no thrills, no freedom.
