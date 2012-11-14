---
layout: page
title: Welcome
tagline: Supporting tagline
---
{% include JB/setup %}

<spam class="post-home-title"><a href="{{ BASE_PATH }}{{ site.posts[0].url }}">{{ site.posts[0].title }}</a></spam>
<div class="post-home-content">{{ site.posts[0].content }}
</div>
<hr class="post-home-separator"/>

{% if site.posts.size > 1 %}
<spam class="post-home-title"><a href="{{ BASE_PATH }}{{ site.posts[1].url }}">{{ site.posts[1].title }}</a></spam>
<div class="post-home-content">{{ site.posts[1].content }}
</div>
<hr class="post-home-separator"/>
{% endif %}

{% if site.posts.size > 2 %}
<spam class="post-home-title"><a href="{{ BASE_PATH }}{{ site.posts[2].url }}">{{ site.posts[2].title }}</a></spam>
<div class="post-home-content">{{ site.posts[2].content }}</div>
<hr class="post-home-separator"/>
{% endif %}

{% if site.posts.size > 3 %}
<spam class="post-home-title"><a href="{{ BASE_PATH }}{{ site.posts[3].url }}">{{ site.posts[3].title }}</a></spam>
<div class="post-home-content">{{ site.posts[3].content }}</div>
<hr class="post-home-separator"/>
{% endif %}

{% if site.posts.size > 4 %}
<spam class="post-home-title"><a href="{{ BASE_PATH }}{{ site.posts[4].url }}">{{ site.posts[4].title }}</a></spam>
<div class="post-home-content">{{ site.posts[4].content }}</div>
<hr class="post-home-separator"/>
{% endif %}


<spam class="post-home-title"><a href="archive.html">Previous posts...</a></spam>
&nbsp;