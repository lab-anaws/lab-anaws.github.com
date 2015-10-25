---
layout: page
title: Advanced Network Architectures and Wireless Systems
tagline: Lab Website
---
{% include JB/setup %}
<ul >
            {% for post in site.posts %}
            <li>
            <a href="{{ post.url }}">
             <h3>{{ post.title }}</h3>
             <p class="blogdate">{{ post.date | date: "%d %B %Y" }}</p>
             <div>{{ post.content |truncatehtml | truncatewords: 60 }}</div>
             </a>
             </li>
            {% endfor %}
</ul>
