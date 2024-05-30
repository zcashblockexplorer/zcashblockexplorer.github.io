---
layout: default
---

## $ cat status.txt
{:id="about"}

After 3 years, we made the difficult decision to shut down the widely used ZcashBlockExplorer.com on June 1st, 2024 due to lack of support & funding. We are deeply grateful for the journey we've shared with you all. 

## $ cat documentation.txt
{:id="projects"}

<ul>
{% for project in site.categories.projects %}
<li><a href="{{ project.link }}">{{ project.title }}</a> - {{ project.description }}</li>
{% endfor %}
</ul>

## $ cat source.txt
{:id="tools"}

<ul>
{% for tool in site.categories.tools %}
<li><a href="{{ tool.link }}">{{ tool.title }}</a> - {{ tool.description }}</li>
{% endfor %}
</ul>
