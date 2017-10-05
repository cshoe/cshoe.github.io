---
title: "Readability"
date: 2012-12-01
logo:
  url: /assets/images/readability/logo.png
  alt: "Readability"
description: "Read comfortably anytime, anywhere."
excerpt: "Read comfortably anytime, anywhere."
sidebar:
  - title: "Role"
  - text: "Software Engineer"
  - title: "Tech"
  - text: "Python, Django, AWS, MySQL, Memcached"
gallery:
  - url: /assets/images/readability/homepage.png
    image_path: assets/images/readability/homepage.png
    alt: "Readability homepage"
  - url: /assets/images/readability/ipad.jpg
    image_path: assets/images/readability/ipad.jpg
    alt: "Readability iPad app screenshot"
  - url: /assets/images/readability/extension.png
    image_path: assets/images/readability/extension.png
    alt: "Readability browser plugin screenshot"
layout: project
---
<p>
    Readability was a bookmarking service hooked up to a powerful parsing engine. It stripped away clutter and placed a page's content in a configurable interface. A user could choose from different fonts, font sizes, colors and line width to create a reading interface that was comfortable. The service had its roots in a browser plugin that went on to <a href="https://www.theregister.co.uk/2010/06/08/safari_reader_based_on_open_source_project/" rel="external">inspire Apple's Safari Reader</a>. Many found the service useful. The iOS apps were featured by Apple and there were over a million users on the platform.
</p>

<p>
    There were three big features I worked on at Readability: tagging, Facebook integration and Recommendations. Integrating with Facebook meant  both authentication and creating custom OpenGraph objects for the platform. This enabled users to easily share what they were reading as well as allowing us to have a bit of control over how bookmarks and articles were presented on Facebook.
</p>

<p>
    Readability was a Django monolith using MySQL to store data. Memcached was heavily relied on (possibly abused) as the user base grew. It was deployed to AWS using the usual suspects -- EC2, Elasticache, RDS, S3 and Cloudfront.
</p>
