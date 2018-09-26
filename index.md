---
layout: page
title: Advanced Network Architectures and Wireless Systems
tagline: Lab Website
---
{% include JB/setup %}

This is the lab page of the *Advanced Network Architectures and Wireless Systems* course held within the second year program of L.M. in Computer Engineering of the Dept. of Information Engineering of the University of Pisa by [Prof. Enzo Mingozzi](http://www2.ing.unipi.it/~a009395/home/index.htm).
The lab classes are held by [Dr. Carlo Vallati](http://www.iet.unipi.it/c.vallati/).
This page contains specific material for the lab classes. General material for the course can be found [here](http://www2.ing.unipi.it/~a009395/corsi/anaws/index.shtml).

<ul style="list-style: none;">
            {% for post in site.posts %}
		    {% assign currentDate = post.date | date: "%Y" %}
			{% if currentDate == "2018" %}
		            <li>
		            <a href="{{ post.url }}">
		             <h3>{{ post.title }}</h3> </a>
		             <p class="blogdate">{{ post.date | date: "%d %B %Y" }}</p>
		             <div>{{ post.content }}</div>
		             </li>
			{% endif %}
            {% endfor %}
</ul>
