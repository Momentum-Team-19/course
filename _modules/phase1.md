---
title: Phase 1
phase: 1
published: true
---

{% assign topics = site.data.phase1.topics | sort: 'date' | reverse | where: "published", "true" %}
{% assign projects = site.data.phase1.projects %}
{% assign demos = site.data.phase1.demos %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: {% if topic.page %} [{{ topic.title }}]({% link {{topic.page}} %}){% else %} {{topic.title}} {% endif %}
: {% if topic.post_today %} [Post]({% link posts.md %}){: .label .post-label } {% endif %}[Project]({{ projects[topic.project_name].url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .project-label } {% if topic.code_demo %} [Demo]({{ topic.code_demo }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .code-demo-label } {% endif %}
{% endfor %}
