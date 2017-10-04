---
title: "Readability"
date: 2012-12-01
logo:
  url: /assets/images/readability/logo.png
  alt: "Readability"
description: "A bookmarking service hooked up to a powerful parsing engine."
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

<p>Readability was a bookmarking service hooked up to a powerful parsing engine. It stripped away clutter and placed a page's content in a configurable interface. A user could choose from different fonts, font sizes, colors and line width to create a reading interface that was comfortable. The service had it's roots in a browser plugin that went on to <a href="https://www.theregister.co.uk/2010/06/08/safari_reader_based_on_open_source_project/" rel="external">inspire Apple's Safari Reader</a>. Many found the service useful. The iOS apps were featured by Apple and there were over a million users on the platform.</p>

<p>There was some controversy around Readability. Removing ads from a webpage obviously isn't ideal for those who depend on advertising revenue. Surprisingly that wasn't the most controversial aspect. Well before micro-payments were a mainstream discussion, Readability experimented with a business model aiming to support itself and content creators. The model had it's flaws but was an honest exploration into a new way to support content creators on the web.</p>

<p>Another controversial aspect of Readability had to do with paywalls. With the design of the platform, it was possible to serve content that should have otherwise been behind a paywall to users who weren't paying the publisher. I was personally torn on the subject because these design decisions had a beneficial consequence as well. Firewalls were bypassed the same way paywalls were. Because of this, we had a large amount of traffic coming from countries who attempted to limit what is available to their citizens on the Internet.</p>

<p>There were three big features I was proud to work on at Readability: tagging, Facebook integration and recommendations. The Facebook integration used custom OpenGraph objects to allow users to share bookmarks. Recommendations were a significant part of a new version of the platform. It encouraged sharing on the platform and removed the need for <a href="{% link _work/mustread.md %}">Mustread</a>.</p>

<p>More than these features or the service itself, I was proud to be a part of the team. In addition to crafting the frontend, <a href="https://tylergaw.com/" rel="external">Tyler Gaw</a> pushed the vision of the platform forward, <a href="https://twitter.com/philipforget" rel="external">Philip Forget</a> made the hard technical decisions, and <a href="https://twitter.com/gooeyblob" rel="external">Kevin O'Connor</a> kept the thing running. <a href="http://mciarlo.com/" rel="external">Mike Ciarlo</a> and <a href="https://twitter.com/zeeshanlakhani" rel="external">Zeeshan Lakhani</a> created a beautiful iOS app. The whole thing was the brain child of <a href="http://www.umbrae.net/" rel="external">Chris Dary.</a></p>

<p>Technically, Readability was a Django monolith using MySQL to store data. Memcached was heavily relied on (possibly abused) as the user base grew. It was deployed to AWS but we never quite made the move to immutable infrastructure.</p>
