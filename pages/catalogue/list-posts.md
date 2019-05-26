{%for post in sorted-posts %}
<ul>
    <li><a href="{{ post.url | remove: "/"}}">{{ post.title }}</a></li>
</ul>
{% endfor %}