---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
permalink: /
---
# This is a site for some mini blogs ,to sort thouths or share or update! {#hello-jekyll}

{% for post in site.posts %}
<h2>{{post.title}}</h2>
<h3>{{post.categories}}</h3>
{% endfor %}

{% assign names = "Billy, Bob, Joel" | split: ', ' %}
<ul>
    {% for name in names %}
    <li>{{ name }}</li>
    {% endfor %}
</ul>


check out other pages
- [About](/about/)
