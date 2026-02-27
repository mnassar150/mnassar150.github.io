---
layout: home
title: "Identity in Depth"
---

Welcome to **Identity in Depth** — technical articles on Microsoft Entra ID, 
Zero Trust architecture, Exchange Online, and regulatory compliance for 
European financial institutions.

{% for post in site.posts limit:6 %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %Y" }} · {{ post.categories | join: ", " }}*

{{ post.excerpt }}

---
{% endfor %}
