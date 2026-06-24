---
layout: default
title: Blog
permalink: /blog/
---

# Blog

More info to come :)

[Subscribe via RSS]({{ "/feed.xml" | relative_url }})

<ul class="post-list">
{% for post in site.posts %}
  <li class="post-list-item">
    <h2 class="post-list-title">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h2>
    <p class="post-list-meta">
      <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time>
    </p>
    <p class="post-list-excerpt">{{ post.excerpt | strip_html | truncate: 200 }}</p>
  </li>
{% endfor %}
</ul>


{% if site.posts.size == 0 %}
<p>No posts yet. Check back soon!</p>
{% endif %}
