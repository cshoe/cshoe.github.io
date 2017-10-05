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
<p>
    The concept of Lofty was simple -- create a vacation rental market place with more European supply than Airbnb. The perception was Airbnb was supplying American properties to American and international demand but was lagging behind in getting European properties on board. Lofty attempted to beat them to the punch by partnering with many small companies throughout Europe to provide a single marketplace for European vacation rentals.
</p>

<p>
    Aggregating properties from many disparate sources proved to be challenging. Some companies offered a SOAP API while others provided XML documents periodically dumped to FTP servers. Working on this ingestion process taught me just how complicated calendar data can be. Each company had different states for a day -- available, available but can't check-in, available but can't checkout and unavailable to name a few. The amount of calendar data the platform needed to track grew exponentially with respect to the number of properties. This complexity bled into other fundamental pieces of the service like the logic to tell if a property could be booked for a given date range. The ingestion process ended up running but the delays ended up being too much for the company to absorb.
</p>

<p>
    Technically, Lofty was a monolithic Django app. For better geo performance, it used PostgreSQL despite Amazon not supporting it with RDS at the time. Memcached kept data readily available. Standard AWS offerings -- S3, Cloudfront, EC2, Elasticache -- were all leveraged in development and production environments.
</p>
