---
layout: post
title: "Please, don't build software like bridges"
description: ""
category: 
tags: [software-development]
---
{% include JB/setup %}

Few days ago, I found myself writing a loooong answer to [this post](https://medium.com/on-product-management/9264314b8965). It's written by one of my new co-workers, so I thought a response-post could be a better idea.

I totally agree with most of the points of the article: we should get feedback from users in order to be able to give them a valid solution. Otherwise your product will be totally useless, solving "problems" that nobody has.

But the question is: **what is the best way to get this feedback?** and, **are you and your users able to give you the right feedback when you reach them at first?**

Probably those women didn’t know how important was the far-distance-well for their lives and they discovered it just when they experimented other ways. Or maybe they knew that the far-well was important, but needed to live without it, in order to balance the pros and cons or having water at home. Who knows, the clue is: it use to be quite challenging to discover some kind of things with certainty without experimenting with them.

Unfortunately, common sense (and engineering-way of thinking) said to us the opposite, and we always try to reach the right and final solution at the first attempt, but it's not always feasible, or it could be possible, but it needs an extremely hard planification and design phases. Engineering-way of building things (like wells, bridges or roads) spend **a lof of time** in these preliminary phases, just because they cannot use "trial and error": if they fail in the first attempt, the waste of time and money is so high that they cannot afford a second chance.

But fortunately software is quite different because the *cost of failure* is relatively low: you can fail once, twice or even more time, learn thru the process, and deliver a better product in the next (maybe the last) try. That's why one of the easiest ways to get right feedback in software is through *prototyping and experimenting* [this article about game development approaches](http://www.lostgarden.com/2007/02/rockets-cars-and-gardens-visualizing.html) explains it much better than me, so please, read it for more details). And this way gives you a nice-to-have side effect: it forces you to write code in such a way that it's flexible, simple and ready to allow the change, no matter how big it is.

This way of working thru iterations is so powerful that even physical products are been building using this approach: Apple's products follow this rule: first versions of gadgets tend to be very limited, and then they improve version by version, meeting market expectations and customers needs. It would be much faster and cheaper to build the perfect smartphone in the first shoot, but that's a pipe-dream and they need to iterate over and over again.

In summary: if you're writing software, don't make too many assumptions in your first attempt, don't waste too much time analysing, designing, architecting and planning: just build a simple enough prototype, give it life and see how it breathes (if it does). Then get real-world feedback and change towards that direction. Repeat until your users become fans, like Apple ones (:
