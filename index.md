---
layout: default
title: Home
---

<div class="intro">
</div>

## About Me

I'm John, a developer from Saskatchewan. I'm the kind of person who loves wearing different hats, which is on full display in my current role as the Tech Lead at the Saskatchewan Roughrider Football Club, where I've been since 2019.

I'm a big proponant of "boring" technologies like Django and HTMX while also taking plenty of time to explore what's going on in the hype cycles.

## Recent Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Get in Touch

Feel free to reach out if you’d like to admire my side project graveyard or just say hello. You can find me on the following platforms:
- [GitHub](https://github.com/johnphillips114)
- [LinkedIn](https://linkedin.com/in/john-phillips-56459214a/).
- [Mastodon](https://mapstodon.space/@oxlox)
- [Bluesky](https://bsky.app/profile/oxlox.ca)
