---
title: "Lofty"
date: 2010-02-01
show_title: false
logo:
  url: /assets/images/lofty/logo.png
  alt: "Lofty logo"
description: "An Airbnb clone that never really got off the ground..."
excerpt: "An Airbnb clone that never really got off the ground..."
sidebar:
  - title: "Role"
  - text: "Software Engineer"
  - title: "Tech"
  - text: "AWS, Python, Django, Memcached, PostgreSQL"
layout: project
---

<p>Lofty was another source of firsts for me. It was my first time working on a production Python/Django app, my first time deploying something to "the cloud", my first interaction with geo queries and the first place I met <a href="https://twitter.com/0x71" rel="external">Corey</a>, who has remained a friend and co-worker over the years.</p>

<p>The concept of Lofty was simple but the implementation proved a bit more difficult. It attempted to take the Airbnb model and flip the supply/demand aspect. The perception was Airbnb was supplying American properties to American and international demand but was lagging behind in providing substantial European supply. Lofty attempted to beat them to the punch by aggregating properties managed by many small companies throughout Europe to provide a single marketplace for European vacation rentals. This aggregation was the main technical challenge at Lofty and taught me just how complex calendar data can be. Any day could take one of nearly ten different states. Because of this, calendar data grew exponentially with respect to the number of properties in the system.</p>

<p>Technically, Lofty was a monolith Django app. For better geo performance, it used PostgreSQL despite Amazon not supporting it with RDS at the time. Memcached kept data readily available. Standard AWS offerings -- S3, Cloudfront, EC2, Elasticache -- were all leveraged in development and production environments.</p>
