---
layout: default
title: Identity & Access
permalink: /pages/identity-access/
---

<p style="font-size:0.85em;margin-bottom:1.5em;">
  <a href="/">← Home</a> &nbsp;&middot;&nbsp;
  <a href="/pages/zero-trust/">Zero Trust</a> &nbsp;&middot;&nbsp;
  <a href="/pages/exchange/">Exchange</a> &nbsp;&middot;&nbsp;
  <a href="/pages/automation/">Automation</a> &nbsp;&middot;&nbsp;
  <a href="/pages/compliance/">Compliance</a>
</p>

Articles on Microsoft Entra ID configuration, application consent policies, Conditional Access, Privileged Identity Management, and identity lifecycle management.

---

{% for post in site.posts %}
{% if post.categories contains 'identity-access' %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endif %}
{% endfor %}

*More articles coming soon. Topics in progress: Entra ID PIM configuration, Access Reviews, and SSPR policy design.*

<p style="font-size:0.85em;margin-top:2em;">
  <a href="/">← Home</a> &nbsp;&middot;&nbsp;
  <a href="/pages/zero-trust/">Zero Trust</a> &nbsp;&middot;&nbsp;
  <a href="/pages/exchange/">Exchange</a> &nbsp;&middot;&nbsp;
  <a href="/pages/automation/">Automation</a> &nbsp;&middot;&nbsp;
  <a href="/pages/compliance/">Compliance</a>
</p>
