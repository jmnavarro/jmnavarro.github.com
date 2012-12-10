---
layout: post
title: "BigDataSpain Conf 2012"
description: ""
category: 
tags: [bigdata, conference]
---
{% include JB/setup %}

Yesterday I was in the [BigDataSpain Conference](http://www.bigdataspain.org/) listening talks of some international speakers. You don't have the opportunity to listen people from [Cassandra](http://cassandra.apache.org/), [Apache Pig](http://pig.apache.org/) (part of Hadoop stack) or [BigQuery](https://developers.google.com/bigquery/) every day, so it was quite interesting and enlightening. 

Some thoughts of talks I consider more interesting:
 *   [Jonathan Bruner](http://www.linkedin.com/in/brunerjon) gave an historical introduction of Big data discipline and dazzled everybody with success stories about systems using big data years or even centuries ago. I missed this talk (damn it!) but people said it was one of the best.
 *   [Jonathan Ellis](www.linkedin.com/in/jbellis) gave a nice introduction of Cassandra explaining why is (should be?) so fast, scalable and reliable ("indestructible" as he said). 
 *   [Alan Gates](http://www.linkedin.com/pub/alan-gates/2/45a/181) made an overview of the typical toolbox for developing bigdata systems under hadoop: pig, hive, hcatalog... too messy for me. I really didn't understand the point.
 *  [Nati Shalom](http://www.linkedin.com/in/natishalom) ([slides](http://ht.ly/flbrP)) talked about cloud and how to integrate/migrate our systems from/to different cloud systems. One thing he mentioned was the case of Zynga, where due to astronomical cost to operate their systems with AWS (million of dollars) decided to invest in an in-house datacenter (private cloud called zCloud) and only use AWS in order to support peaks of demand. Controlled costs together with flexibility, I like it! Also presented his product "Cloudify", a sort of cloud abstraction layer (quite interesting).
 *  [Jordan Tigani](www.linkedin.com/in/jordantigani) talked about [BigQuery](https://developers.google.com/bigquery/), a cloud bigdata store for interactive queries. He showed some SQL-like queries running against several hundred gigabytes table. BigQuery responses in less than 30 seconds, doing filters, agroupations, sumarizations... absolutely impressive. The worst: answering a question, he didn't have a clear idea how to populate a multi-gigabyte store trough Internet. A huge RESTful POST? One POST a day? Quite fun.
 *  [Brendan McAdams](www.linkedin.com/in/bwmcadams) gave the funiest talk. Quite educational, talked about map-reduce basics, some phylosophical sides of software development ("Software is eating the world", as he said). It's too bad he didn't talk about mongoDB (every of us expected that).


One of the topics everybody (even speakers) repeated was: "but, what is bigdata really?". Some refered to the ammount to information to store and process, others to the speed of the processing, others to the troughtput of input data against output... but I really liked Jorgan Tigani answer: "Bigdata is when the cost of throw your data is higher than the cost of store and process it". Brilliant!