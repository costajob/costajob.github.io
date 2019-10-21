---
layout:     post
title:      "Duplo Blocks"
date:       2018-06-21 09:41:33 +0200
categories: code
---

On these days i am helping to draw some high level (aka no coding) diagrams for the integration of several enterprise (the word scares me out each time) applications part of an e-commerce system.

Typically, when i have the benefit to design the software from scratch, i stick to the Gal’s Law: starting minimal with a working system and adding new components only when strictly necessary.

This is not the case: i have been suggested to adopt an enterprise service bus (ESB) component in order to centralize all the interactions and avoid a scenario called the spaghetti integration.

Luckily, for me, the customer has picked the less enterprise ESB on the marked, the community edition of the Mule runtime: a piece of software, Java  based, which has started small as an open source project and has grown to the point that a big company purchased it, making it a perfect picking for Gartner Magic Quadrant (and thus falling within corporates radar).

I grabbed a book and checked the online documentation (complete, but deceiving) and soon realized you don’t need to write a single line of Java to let the ESB work.

Working with these softwares reminds me like playing with the Lego™ Duplo blocks, something i generally dislike, being a fan of the Technic line.

Like with Duplo you just need to grab the right macro-block, like the protocol adapter the application receive data from, and combine it with the others available to compose an acceptable Legos.

While the benefits of this is obviously clear (at least for a consultancy), it is a concept i always struggled with as a programmer: you do not need a Java developer (if a developer at all), to deploy a working Mule instance, you just need a product expert.

I’d like experts start realizing that Duplo blocks are indeed build on small Technic ones: the awareness you can compose much more with micro-blocks is refreshing, but at the same time leave you hungry for more.

At the end, this is what programming is all about.
