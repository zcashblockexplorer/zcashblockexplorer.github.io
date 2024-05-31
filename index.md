---
layout: default
---
{:id="about"}

After 3 years, we made the difficult decision to shut down the widely used, tracker-free ZcashBlockExplorer.com on May 31st, 2024 due to lack of support & funding. We are deeply grateful for the journey we've shared with you all. 

{:id="tools"}

<ul>
{% for tool in site.categories.tools %}
<li><a href="{{ tool.link }}">{{ tool.title }}</a> - {{ tool.description }}</li>
{% endfor %}
</ul>

{:id="projects"}

<ul>
{% for project in site.categories.projects %}
<li><a href="{{ project.link }}">{{ project.title }}</a> - {{ project.description }}</li>
{% endfor %}
</ul>