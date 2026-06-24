---
layout: default
title: Home
---

<div class="intro">
</div>

## About Me

I'm John, a developer from Saskatchewan. I'm the kind of person who loves wearing different hats, which is on full display in my current role as the Tech Lead at the Saskatchewan Roughrider Football Club, where I've been since 2019.

Some of my interests are basketball, football (Canadian and American), maps, geography, and most of all, being a dad :)

## Recent Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Get in Touch

Feel free to reach out if you’d like to admire my side project graveyard or just say hello. You can find me on the following platforms:
- [GitHub](https://github.com/johnphillips114)
- [LinkedIn](https://linkedin.com/in/john-phillips-56459214a/).
- [Bluesky](https://bsky.app/profile/oxlox.ca)
