---
permalink: /news/
title: "News"
id: "News"
hidden: true
    
---

<ul>
   {% for post in site.posts %}
     <li>
       <a href="/geosmartsite{{ post.url }}">{{ post.title }}</a>
     </li>
   {% endfor %}
</ul>





