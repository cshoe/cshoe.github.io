---
layout: single
title: "Work"
permalink: /work/
author_profile: true
---
<p>
    I've been writing software professionally for over 10 years. I've helped build fundraising platforms for a <a href="{% link _work/mycharitywater.md %}">non-profit</a> and a <a href="{% link _work/the-groundwork.md %}">Presidential campaign</a>, a custom CMS for an <a href="{% link _work/reuters-next.md %}">international news organization</a>, data pipelines and build tools.
</p>

<p>
    I enjoy tedious problems like query performance as well as the blue-sky design phase. I think clean solutions start with requirements gathering and try to apply campsite rules to codebases, leaving them better than I found them.
</p>

<p>
    I'm currently looking for an opportunity to leverage my past experience and work in new spaces like mobile, desktop apps, operating systems and games.
</p>

<div class="skills-list-wrapper">
    <h4>I've Used These in Production Environments</h4>
    <div class="skills-list">
        <h4>Languages</h4>
        <ul>
            <li>Python</li>
            <li>Javascript</li>
            <li>Java</li>
            <li>PHP</li>
            <li>COBOL</li>
        </ul>
    </div>
    <div class="skills-list">
        <h4>Frameworks</h4>
        <ul>
            <li>Django</li>
            <li>Tornado</li>
            <li>Flask</li>
            <li>jQuery</li>
            <li>Backbone.js</li>
        </ul>
    </div>
    <div class="skills-list">
        <h4>Datastores</h4>
        <ul>
            <li>MySQL</li>
            <li>PostgreSQL</li>
            <li>MongoDB</li>
            <li>DynamoDB</li>
            <li>Memcached</li>
            <li>Redis</li>
        </ul>
    </div>
    <div class="skills-list">
        <h4>Tools</h4>
        <ul>
            <li>Spinnaker</li>
            <li>Travis CI</li>
            <li>Jenkins</li>
            <li>Ansible</li>
            <li>Puppet</li>
        </ul>
    </div>
</div>

<div class="skills-list-wrapper">
    <h4>I've Tinkered With These</h4>
    <div class="skills-list">
        <h4>Languages</h4>
        <ul>
            <li>C</li>
            <li>Go</li>
            <li>Swift</li>
            <li>Objective-C</li>
        </ul>
    </div>
    <div class="skills-list">
        <h4>Frameworks</h4>
        <ul>
            <li>AngularJS</li>
            <li>React</li>
            <li>Node.js</li>
        </ul>
    </div>
    <div class="skills-list">
        <h4>Datastores</h4>
        <ul>
            <li>Elasticsearch</li>
        </ul>
    </div>
    <div class="skills-list">
        <h4>Tools</h4>
        <ul>
            <li>Packer</li>
            <li>Docker</li>
            <li>Salt</li>
            <li>Chef</li>
        </ul>
    </div>
</div>

{% assign posts = site.work | sort: 'date' %}

<h2>Projects</h2>

<div id="project__grid-wrapper" class="grid__wrapper">
  {% for post in posts reversed %}
    {% include project-single-grid.html type="grid" %}
  {% endfor %}
</div>
