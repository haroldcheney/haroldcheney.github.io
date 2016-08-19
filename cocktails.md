---
layout: page
title: Cocktails
permalink: /cocktails/
---
Feel free to use any of these for any legal purpose. If you enjoy any of them,
I'd love to hear about it!

<ul>
{% for cocktail in site.cocktails %}
      <li>
        <a href="{{ cocktail.url }}">{{ cocktail.title }}</a>
      </li>
{% endfor %}
</ul>
