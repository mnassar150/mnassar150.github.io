---
layout: default
title: Compliance
permalink: /pages/compliance/
---

<p style="font-size:0.85em;margin-bottom:1.5em;">
  <a href="/">← Home</a> &nbsp;&middot;&nbsp;
  <a href="/pages/identity-access/">Identity &amp; Access</a> &nbsp;&middot;&nbsp;
  <a href="/pages/zero-trust/">Zero Trust</a> &nbsp;&middot;&nbsp;
  <a href="/pages/exchange/">Exchange</a> &nbsp;&middot;&nbsp;
  <a href="/pages/automation/">Automation</a>
</p>

Regulatory compliance guides for European financial institutions — DORA, BaFin BAIT, and audit readiness using Microsoft security controls.

---

{% for post in site.posts %}
{% if post.categories contains 'compliance' %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endif %}
{% endfor %}

*More articles coming soon. Topics in progress: BaFin BAIT full control mapping, DORA ICT incident classification, and audit evidence collection.*

<p style="font-size:0.85em;margin-top:2em;">
  <a href="/">← Home</a> &nbsp;&middot;&nbsp;
  <a href="/pages/identity-access/">Identity &amp; Access</a> &nbsp;&middot;&nbsp;
  <a href="/pages/zero-trust/">Zero Trust</a> &nbsp;&middot;&nbsp;
  <a href="/pages/exchange/">Exchange</a> &nbsp;&middot;&nbsp;
  <a href="/pages/automation/">Automation</a>
</p>
