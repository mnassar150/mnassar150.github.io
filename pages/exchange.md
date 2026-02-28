---
layout: default
title: Exchange & Messaging
permalink: /pages/exchange/
---

<p style="font-size:0.85em;margin-bottom:1.5em;">
  <a href="/">← Home</a> &nbsp;&middot;&nbsp;
  <a href="/pages/identity-access/">Identity &amp; Access</a> &nbsp;&middot;&nbsp;
  <a href="/pages/zero-trust/">Zero Trust</a> &nbsp;&middot;&nbsp;
  <a href="/pages/automation/">Automation</a> &nbsp;&middot;&nbsp;
  <a href="/pages/compliance/">Compliance</a>
</p>

Practical guides on Exchange Online administration, mail flow architecture, retention policies, PGP encryption, and third-party migrations.

---

{% for post in site.posts %}
{% if post.categories contains 'exchange' %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endif %}
{% endfor %}

*More articles coming soon. Topics in progress: Hybrid mail flow, connectors, and compliance archiving.*

<p style="font-size:0.85em;margin-top:2em;">
  <a href="/">← Home</a> &nbsp;&middot;&nbsp;
  <a href="/pages/identity-access/">Identity &amp; Access</a> &nbsp;&middot;&nbsp;
  <a href="/pages/zero-trust/">Zero Trust</a> &nbsp;&middot;&nbsp;
  <a href="/pages/automation/">Automation</a> &nbsp;&middot;&nbsp;
  <a href="/pages/compliance/">Compliance</a>
</p>
