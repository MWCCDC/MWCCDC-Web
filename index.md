---
layout: default
title: Home
---

<section class="hero">
  <p class="tagline">&gt; initiate_midwest_defense --season 2027</p>
  <h1>Midwest Regional Collegiate Cyber Defense Competition</h1>
  <p>Teams of students from two- and four-year institutions face off by building and
  defending mock business infrastructures — protecting their systems from professional
  red teams tasked with taking them offline and breaching their security.</p>
</section>

## About the Competition

Colleges and universities from across the Midwest bring together their top tech talent
to compete in the MWCCDC. While teams work tirelessly to fend off cyber attacks,
judges introduce network enhancement and upgrade challenges that contribute to
scoring and overall event success.

**No prior competition experience required.**

## Upcoming Schedule — 2027 Season

{% for event in site.data.schedule.events %}
- **{{ event.name }}** — {{ event.date | date: "%A, %B %-d, %Y" }}
{% endfor %}

Second and third place teams from each state qualifier earn a spot in the Wildcard
CCDC. Top winners of each state CCDC and the Wildcard advance to the
Erich J. Spengler Midwest Regional CCDC.