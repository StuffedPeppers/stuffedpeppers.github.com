---
layout: default
title: Stuffed Peppers | The Blog
---

<article id="home">
  <!-- <h2>Posts</h2> -->
  <ul class="homelist posts">
    {% for post in site.posts limit:5 %}
        <li><span>{{ post.date | date_to_string }}</span> <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <h4 class="center readmore"><a href="/archive.html">View all posts</a></h4>
  
</article>
