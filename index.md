我的读书笔记

{% for page in site.html_pages %}
<p><a href="{{ page.url }}">{{ page.title }}</a><br>
<span style="font-size:.8em;font-weight:bold;">{{ page.date | date: "%B %e, %Y" }}</span></p>
{% endfor %}
