---
title: "The Groundwork"
date: 2014-08-01
logo:
  url: /assets/images/the-groundwork/logo.png
  alt: "The Groundwork"
description: "A platform for modern movements."
excerpt: "A platform for modern movements."
sidebar:
  - title: "Role"
  - text: "Senior Software Engineer"
  - title: "Tech"
  - text: AWS, Python, Django, Tornado, Ansible, Travis CI, Datadog
gallery:
  - url: /assets/images/the-groundwork/homepage.png
    image_path: assets/images/the-groundwork/homepage.png
    alt: "The Groundwork homepage"
  - url: /assets/images/the-groundwork/scalable.png
    image_path: assets/images/the-groundwork/scalable.png
    alt: "Scalable, secure platform"
  - url: /assets/images/the-groundwork/testimonies.png
    image_path: assets/images/the-groundwork/testimonies.png
    alt: "The Groundwork testimonies"
layout: project
---
<p>
    Non-profits use The Groundwork to raise money, host events and collect data. It played a key role in Hillary Clinton's 2016 Presidential campaign.
</p>

<p>
    My main focus on The Groundwork was donation processing. I also worked on the main data pipeline that ran through the platform terminating in Elasticsearch as well as  a service to collect arbitrary data which leveraged <a href="http://json-schema.org/" rel="external">JSON Schema</a> to validate input. These data flows combined with a rules engine allowed organizations to put their data to work for them.
</p>

<p>
    During the Hillary For America campaign, The Groundwork supported:
</p>
<ul>
    <li>9 million donations, totalling $600 million</li>
    <li>36 million supporter signups</li>
    <li>2 million event RSVPs</li>
    <li>60 million transactional emails</li>
    <li>3 million user accounts</li>
</ul>

<p>
    Python was used extensively across the platform and there were build tools written in Java and sidecar services in Go. Ansible configured machines, Packer built AMIs to be deployed to ASGs while Datadog and Pagerduty provided insight and monitoring capabilities.
</p>
