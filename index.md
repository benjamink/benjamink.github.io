---
layout: page
title: Welcome to SuperK!
tagline: My tech blog
---
{% include JB/setup %}

<img src="/assets/images/BenK_Avatar.png" style="float: left; height: 100px; border: none;"/>
Welcome to my technical blog where I share some of the technical things I do.  You'll find topics here ranging from systems administration, Raspberry Pi fiddlings, cars, boats, various out-doorsy things, some ramblings on various social & cultural topics that interest me, etc.  Nothing on here is likely entirely correct & I make no claims to accuracy.  Use anything here at your own risk & good luck!

<ul>
  {% assign posts_collate = site.posts %}
  {% include JB/posts_collate %}
</ul>
