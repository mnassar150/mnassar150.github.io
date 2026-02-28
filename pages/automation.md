---
layout: default
title: Automation
permalink: /pages/automation/
---

<p style="font-size:0.85em;margin-bottom:1.5em;">
  <a href="/">← Home</a> &nbsp;&middot;&nbsp;
  <a href="/pages/identity-access/">Identity &amp; Access</a> &nbsp;&middot;&nbsp;
  <a href="/pages/zero-trust/">Zero Trust</a> &nbsp;&middot;&nbsp;
  <a href="/pages/exchange/">Exchange</a> &nbsp;&middot;&nbsp;
  <a href="/pages/compliance/">Compliance</a>
</p>

PowerShell scripts, Microsoft Graph API guides, and workflow automation for identity and messaging administration.

---

{% for post in site.posts %}
{% if post.categories contains 'automation' %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endif %}
{% endfor %}

*More articles coming soon. Topics in progress: Graph API bulk operations, automated access reviews, and lifecycle management scripts.*

<p style="font-size:0.85em;margin-top:2em;">
  <a href="/">← Home</a> &nbsp;&middot;&nbsp;
  <a href="/pages/identity-access/">Identity &amp; Access</a> &nbsp;&middot;&nbsp;
  <a href="/pages/zero-trust/">Zero Trust</a> &nbsp;&middot;&nbsp;
  <a href="/pages/exchange/">Exchange</a> &nbsp;&middot;&nbsp;
  <a href="/pages/compliance/">Compliance</a>
</p>
