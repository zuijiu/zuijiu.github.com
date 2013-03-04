---
layout: default
title: sgbn's little cabin
---

# About me

  I got this name Sagebane form a pop novel &lt;A song of ice and fire&gt;,
  there is a lord named Whorebane Umber, it indicates that he is a
  famous whore killer. though I found bane something is funny, Why not
  bane something myself? So I chosed the sage to bane..

# Related posts

<ul class="posts">
{% for post in site.posts limit: 5 %}
  <div class="post_info">
    <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
            <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </br> <em>{{ post.excerpt }} </em>
    </div>
  {% endfor %}
</ul>
