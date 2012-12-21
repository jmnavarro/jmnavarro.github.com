---
layout: post
title: "Vizzualizing deforestation"
description: "Hackathon project for Vizzuality"
category: projects
tags: [ipad, 3d]
---
{% include JB/setup %}

Last summer, I had the chance to spend few hours with the guys of [Vizzuality](http://vizzuality.com/). They're quite good doing time based visualizations, or "stories that matters", as they're used to say, and his product [CartoDB](http://cartodb.com/) is awesome for store, manage and query geospartial data.

So, because of it was a great opportunity to build something cool, we started to work together in order to make a 3D visualization of Indonisia deforestation in the last years.

The backend used was CartoDB through their [SQL API](http://developers.cartodb.com/documentation/cartodb-apis.html#sql_api) and my [CartoDB objective-C client](https://github.com/jmnavarro/cartodb-objectivec-client).
On the client side, we used and early version of [WhirlyGlobe](https://github.com/mousebird/WhirlyGlobe). It's too bad some weeks after that, [Steve Gifford](http://mousebirdconsulting.blogspot.com.es/) released an easy-to-use component, so I had to fight with the codebase, which was a mess of C, C++, Objective-C and Objective-C++, pretty difficult to understand and adapt. Anyway, it seems it was not as bad as I thought, because as Steve said, "you've done some really advanced things and used some features even I rarely use."

I'm pretty proud of the result, especially considering I spent two fulltime days and one week more doing 1-2 hours a day.

Here you can see it running in the iPad simulator:

<object width="480" height="385"><param name="movie" value="http://www.youtube.com/v/-eiiL19stw0&amp;hl=en_US&amp;fs=1"></param><param name="allowFullScreen" value="true"></param><param name="allowscriptaccess" value="always"></param><embed src="http://www.youtube.com/v/-eiiL19stw0&amp;hl=en_US&amp;fs=1" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="480" height="385"></embed></object>

<br/>

Hope you like it!

*UPDATE:* Steve has [highlighted this tiny project](http://mousebirdconsulting.blogspot.com.es/2012/12/whirlyglobecartodb-demo-and-appnation-iv.html) on his blog. I'm so honored and absolutely grateful!