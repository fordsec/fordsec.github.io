---
layout: page
---

Welcome to FordSec, a computer security research group in
[Haverford College](https://haverford.edu)'s
[computer science](https://www.haverford.edu/computer-science)
department. We work on foundational problems in security, programming
languages, and human-computer interaction.

# News

<ul>
{% for post in site.posts limit:5 %}
<li>
<a href="{{ post.url }}">
({{ post.date | date: "%d %b, %Y" }}) {{ post.title }}
</a>
</li>
{% endfor %}
</ul>

# Projects

TBA

# Meetings

TBA
