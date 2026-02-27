---
layout: post
title: "Entra ID Application Consent Policies: Controlling OAuth Permissions at Enterprise Scale"
date: 2025-01-01
categories: identity-access
tags: [entra-id, consent, oauth, app-governance, security]
excerpt: "How to design and enforce application consent policies in Entra ID to prevent over-permissioned OAuth apps — covering admin consent workflows, permission classification, and app governance in enterprise environments."
---

> **Coming Soon** — This article is currently being written and will be published shortly.

## What This Article Will Cover

OAuth application consent is one of the most consistently underestimated attack surfaces in Microsoft 365 environments. A user granting consent to a malicious third-party app can hand an attacker persistent access to email, files, and calendars — bypassing MFA entirely. This article covers how to lock this down without blocking legitimate business applications.

Planned topics include:

- How OAuth consent works in Entra ID — user consent vs. admin consent vs. tenant-wide consent
- The risk of over-permissioned apps: what attackers can do with `Mail.Read` and `Files.ReadWrite.All`
- Configuring the **Application Consent Policy** — blocking user consent, requiring admin approval
- Setting up the **Admin Consent Workflow** so users can request access without being blocked
- Permission classification — how to categorise low, medium, and high risk permissions
- **App Governance** add-on — anomaly detection for OAuth apps
- Auditing existing consented apps — finding and revoking over-permissioned grants
- DORA mapping: why uncontrolled OAuth consent is an ICT risk management gap

---

*[← Back to Identity & Access](/pages/identity-access/)*
