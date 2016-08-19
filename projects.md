---
layout: page
title: Projects
permalink: /projects/
---
Some things I work on in my spare time.

<ul>
{% for project in site.projects %}
      <li>
        <a href="{{ project.link }}">{{ project.name }}</a>
        <p>{{ project.content }}</p>
      </li>
{% endfor %}
</ul>
