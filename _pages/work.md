---
layout: single
title: "Work"
permalink: /work/
author_profile: true
---
<p>
I've been writing software professionally for over 10 years. I've helped build fundraising platforms for a non-profit and a Presidential campaign, a custom CMS for an international news organization, data pipelines and build tools. I've written COBOL on a mainframe and worked on a parsing engine for the web. I like big systems as well as small tools. I'm most comfortable with Python but feel comfortable in any ecosystem after I figure out dependency management. At the end of the day, the language is just the expression of the solution.
</p>

{% assign posts = site.work | sort: 'date' %}

<h2>Projects</h2>

<div id="project__grid-wrapper" class="grid__wrapper">
  {% for post in posts reversed %}
    {% include project-single-grid.html type="grid" %}
  {% endfor %}
</div>
