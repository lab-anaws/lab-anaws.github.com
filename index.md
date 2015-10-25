---
layout: page
title: Advanced Network Architectures and Wireless Systems
tagline: Lab Website
---
{% include JB/setup %}

<ul style="list-style: none;">
            {% for post in site.posts %}
            <li>
            <a href="{{ post.url }}">
             <h3>{{ post.title }}</h3> </a>
             <p class="blogdate">{{ post.date | date: "%d %B %Y" }}</p>
             <div>{{ post.content }}</div>
             </li>
            {% endfor %}
</ul>
