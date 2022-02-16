---
title: Hello World
layout: "index.njk"
---

hello eleventy

<ul>

{% for post in collections.posts %}
<li>
    <a href="{{ post.url }}">{{ post.data.title }}</a>
</li>
{% endfor %}

</ul>


