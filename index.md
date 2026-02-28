---
layout: default
title: "zeroknown"
---

Notes on M365 security, Entra ID, and zero trust. I write about what I'm learning: identity, automation, compliance, hardening environments for regulated industries. The more I dig, the more there is to find.

---

### Browse by Topic

- [Identity & Access](/pages/identity-access/) — Entra ID, consent policies, conditional access, PIM, lifecycle management
- [Zero Trust](/pages/zero-trust/) — Zero Trust architecture, DORA/BaFin mapping, implementation guides
- [Exchange & Messaging](/pages/exchange/) — Exchange Online, mail flow, retention, migrations
- [Automation](/pages/automation/) — PowerShell, Graph API, workflow automation
- [Compliance](/pages/compliance/) — DORA, BaFin BAIT, audit readiness, governance

---
{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endif %}
{% endfor %}
