---
title: "The Groundwork"
date: 2014-08-01
logo:
  url: /assets/images/the-groundwork/logo.png
  alt: "The Groundwork"
description: "A platform for modern movements. Non-profits use it to raise money, host events and collect data. It played a key role in Hillary Clinton's 2016 Presidential campaign."
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
    Even if you remove the campaign, The Groundwork was the most challenging work of my career. We built a ton of tech for a team our size. There were scalable micro-services, some of the best ops tools and processes I've ever seen, and a message passing concept I was really excited about.
</p>

<p>
    My main focus was on donation processing for most of the campaign. As the election grew closer, I shifted some of my energy to working on the main data pipeline that ran through the platform terminating in Elasticsearch. I also worked on a service to collect user defined data structures which leveraged <a href="http://json-schema.org/" rel="external">JSON Schema</a>. Using JSON Schema enabled the service to validate input according to user defined criteria as well as provide a structure clients could use to build forms. These data flows combined with a rules engine allowed organizations to collect data from many different sources and act. A small example would be the email service sending different receipts based on donation amount without the donation service ever sending a direct request for a receipt.
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
