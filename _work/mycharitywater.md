---
title: "charity: water"
date: 2009-02-08
show_title: false
logo:
  url: /assets/images/mycharitywater/logo.png
  alt: ""
description: "charity: water is a non-profit organization bringing clean and safe drinking water to people in developing countries."
excerpt: "A non-profit organization bringing clean and safe drinking water to people in developing countries."
sidebar:
  - title: "Role"
  - text: "Software Engineer"
  - title: "Tech"
  - text: "Java, JS, CSS, HTML, MySQL, Memcached"
layout: project
---

<p>charity: water was my first step into startups and small organizations. A friend of mine had started as their staff accountant and sent me a text one night letting me know they were looking to hire a developer. At the time, I was working in a cubicle at an insurance company and escaping on weekends to play shows in a hardcore band. Fast-forward a couple months after that initial text and I was checking into a flight with all my belongings in a duffel bag and a backpack.</p>

<p>By 2009, charity: water had made a name for itself in the non-profit space with impressive branding and events. There was a large online presence but they weren't yet the non-profit tech powerhouse they are today. For the first few months, I did odd jobs around the office involving spreadsheets and microsites for things like <a href="https://archive.charitywater.org/twestival/" rel="external">Twestival</a>. Summer rolled in and a small team started working on bringing <a href="https://en.wikipedia.org/wiki/Scott_Harrison_(charity_founder)" rel="external">Scott's</a> vision for crowdsourced fundraising to life under the tutelage of <a href="https://en.wikipedia.org/wiki/Michael_Birch_(businessman)" rel="external">Michael Birch</a>. There were a few iterations of design, lots of conversations around whiteboards and huge pieces of butcher paper and the occasional disagreement.</p>

<p><i>my charity: water </i> was launched in time for the organization's <a href="https://www.charitywater.org/september/" rel="external">September Campaign</a> in 2009. The first month saw hundreds of fundraising campaigns and nearly $400,000 raised. By year's end, more than $1.2M had been raised on the platform through nearly 1,500 campaigns. This accounted for roughly 20% of total funds raised for water projects in 2009*.</p>

<p>The secret sauce of <i>my charity: water</i> was the ability to track donations all the way to the field. Campaigners and donors can see exactly where their money landed complete with GPS coordinates, pictures and a description of the community. I found the problem a bit daunting. On the surface, it appeared to be an incarnation of the <a href="https://en.wikipedia.org/wiki/Knapsack_problem" rel="external">knapsack problem</a>. After banging my head against it for what felt like too long, another developer and I came up with a solution in an Irish bar on a Friday afternoon. The approach was a bit naive and I remember the code using the word "buckets" all over the place but it fulfilled all the requirements. By the time the first money raised on <i>my: charity water</i> made it to the field, we were able to let all the users know exactly where their impact was felt.</p>

<p>On the technical side, <i>my: charity water</i> was pretty simple. The service was written in Java using a weird-ware web framework and the Freemarker template engine. Data was stored using MySQL and made more readily available in Memcached. Akamai delivered assets from the edge to decrease latency and protect the two (yes, just two) web servers from requests for static assets.</p>

<p><i>Disclaimer: charity: water is a full blown technology organization these days. From the outside, the product still appears to be the same but I highly doubt a single line of what I wrote back in 2009 still exists.</i></p>

\* Numbers from <a href="https://d11sa1anfvm2xk.cloudfront.net/about/downloads/cw_09_annual_report.pdf" rel="external">charity: water's 2009 Annual Report</a>
