<h2>{{ site.description | default: site.github.project_tagline }}</h2>
<p>by John Lukach</p>

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>