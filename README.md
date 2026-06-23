# ByHubo ProcureKit — trust page for micro-SaaS

[![ByHubo ProcureKit](https://img.shields.io/badge/product-ProcureKit-3d7a62)](https://byhubo.com)
[![Trust Page example](https://img.shields.io/badge/example-trust.byhubo.com%2Fbyhubo-blue)](https://trust.byhubo.com/byhubo)

**EU buyer asked for a DPA and subprocessor list?** Publish a live Trust Page URL in one sitting.  
Presets for **Clerk · Stripe · Vercel · PostHog · Resend** and more. **Common Paper DPA** download. **Free tier.**

→ **[Create your Trust Page](https://app.byhubo.com/sign-up)** · **[See live example](https://trust.byhubo.com/byhubo)**

---

## The problem

You shipped on the indie stack. A prospect's legal team emails:

> *"Please send your DPA, subprocessor list, and privacy documentation before we proceed."*

You have a Termly privacy policy in the footer. You do **not** have one link with subprocessors + DPA that procurement can open. The deal stalls while you Google Article 28.

## What ProcureKit does

| You get | Why it matters |
|---------|----------------|
| **Trust Page URL** `trust.byhubo.com/you` | Paste one link in the email thread |
| **Subprocessor table** | Clerk, Stripe, Vercel presets with DPA links |
| **Privacy + cookie policies** | From a short wizard |
| **Common Paper DPA PDF** | Standard B2B SaaS terms, pre-filled cover |

**Not** a cookie-banner tool (use Termly). **Not** enterprise GRC (use Vanta). **Procurement unblock** for first EU B2B customers.

## Who this is for

- Micro-SaaS and side projects selling B2B
- Next.js + Clerk + Stripe + Vercel builders
- Founders who got the "scary legal email" and need to reply today

## Free tier

- Trust Page at `trust.byhubo.com/{slug}`
- Policies, subprocessor presets (5 on free), DPA download, cookie banner snippet
- No credit card

## Files in this repo

| File | Use |
|------|-----|
| [clerk-stripe-vercel-subprocessors.md](./clerk-stripe-vercel-subprocessors.md) | Manual subprocessor checklist + DPA links |
| [procurement-reply-email.md](./procurement-reply-email.md) | Copy-paste email when buyers ask for docs |

Prefer the hosted version? **Sign up takes one sitting:** https://app.byhubo.com/sign-up

## Links

- Marketing: https://byhubo.com
- App: https://app.byhubo.com
- Trust pages: https://trust.byhubo.com/{slug}
- LLM context: https://byhubo.com/llms.txt

## Topics

`saas` `gdpr` `dpa` `subprocessor` `compliance` `clerk` `stripe` `vercel` `indie-hacker` `micro-saas` `trust-center` `common-paper` `b2b-saas` `procurement` `privacy`

---

*Not legal advice. ByHubo ProcureKit — paste a URL, not a panic thread.*

## Publish this repo on GitHub

This folder is meant to be pushed as a **public** repo (e.g. `byhubo/trust-kit`) for GitHub search discovery. The application source stays private.

```bash
# From monorepo root — one-time setup
cp -r open /tmp/trust-kit && cd /tmp/trust-kit
git init && git add . && git commit -m "Trust kit templates for micro-SaaS procurement"
gh repo create byhubo/trust-kit --public --source=. --push
```

Add GitHub topics: `saas`, `gdpr`, `dpa`, `clerk`, `stripe`, `vercel`, `compliance`, `trust-center`.
