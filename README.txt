This is my personal web page

Projects:
{% for project in site.projects %}
- {{ project }}
{% endfor %}