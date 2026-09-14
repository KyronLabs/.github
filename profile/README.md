<!-- KyronLabs organization profile.

     Every number here was counted and every link opened before it was written.
     Anything that cannot be checked from the repositories is not on the page:
     see "Where it stands" for what that rules out and why. -->

<div align="center">

<img src="logo.png" width="96" height="96" alt="" />

# KyronLabs

*Your identity. Your data. Your audience.*

[![Stars](https://img.shields.io/github/stars/KyronLabs/kyron?style=social)](https://github.com/KyronLabs/kyron/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/KyronLabs/kyron/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/Status-Alpha-orange.svg)](https://github.com/KyronLabs/kyron/releases)

[Discord](https://discord.gg/kyron) · [Terms](https://kyron-terms-and-privacy.onrender.com/terms.html) · [Privacy](https://kyron-terms-and-privacy.onrender.com/privacy.html)

</div>

---

## ◈ Why

> *Social media does not require surveillance capitalism.*

Kyron is the attempt to prove it: a social app where your identity is a key you
hold, your data leaves with you, and what you make reaches people without being
paid to.

It is **alpha**. Some of that is built and running; some of it is a directory
with a plan in it. This page says which is which, because a front page that
does not is worth nothing to anybody reading it.

---

## ◈ What is actually running

| | |
|:--|:--|
| **Client** | Flutter — Android, Windows and web from one codebase. iOS builds but is not being worked on. |
| **API** | NestJS on Fastify, 17 REST controllers, Prisma over Postgres, deployed on Render. |
| **Identity** | A DID the account proves it controls — `api/src/modules/identity`. Portable, and not rented from us. |
| **Messages** | End-to-end encrypted direct messages. |
| **Feed** | A ranking engine on real engagement signals: interests, follows, likes, dwell time, negative feedback and recency. |
| **AR camera** | MediaPipe face mesh, 478 landmarks. Colour lenses, attachments that track a face, and effects that change one. Lenses are *data*, so new ones ship without an app release. |
| **Media** | Server-side transcode and poster extraction, off the request thread. |

**Not built yet, and named here so nobody has to find out the hard way:** AT
Protocol federation, smart contracts, and a vector database. There is no code
for any of them in any repository in this organization.

---

## ◈ Repositories

| | |
|:--|:--|
| [**kyron**](https://github.com/KyronLabs/kyron) | The app, the API and the web build. Flutter + NestJS + Postgres. |
| [**kyron-lenses**](https://github.com/KyronLabs/kyron-lenses) | The published AR lens catalogue. A lens is JSON and a picture, so merging here puts it on phones with no app release. |
| [**kyron-lens-studio**](https://github.com/KyronLabs/kyron-lens-studio) | A Windows tool for authoring those lenses: paint a sticker, place it on a 3D face, publish. |
| [**design-system**](https://github.com/KyronLabs/design-system) | Colour, spacing, radius and type, and the Flutter theme built from them. |
| [**kyron-live**](https://github.com/KyronLabs/kyron-live) | Live video. **No system yet, on purpose** — the decision, costed, comes before the code. |
| [**Kyron_Terms_and_Privacy**](https://github.com/KyronLabs/Kyron_Terms_and_Privacy) | The two legal pages the app links out to. |

```bash
git clone https://github.com/KyronLabs/kyron.git
cd kyron/app && flutter run
```

---

## ◈ Where it stands

Counted from `main`, not estimated:

| | |
|:--|:--|
| Hand-written source | ~93,000 lines — 59k Dart, 21k TypeScript, 13k JavaScript |
| Tests | 771 Flutter · 443 API, all green, run on every push |
| Platforms shipping | Android and Windows, built and published by CI on every merge |
| Contributors | See the [commit log](https://github.com/KyronLabs/kyron/commits/main) — the number belongs where it is computed, not typed here |

Anything this table cannot count is not in it. Install numbers, coverage
percentages and burn rate are real things to publish once they are measured
somewhere a reader could check.

---

## ◈ Contributing

Contributions are accepted under the Developer Certificate of Origin.

1. Read [`CONTRIBUTING.md`](https://github.com/KyronLabs/kyron/blob/main/CONTRIBUTING.md)
2. Sign your commits — `git commit -s`
3. Open a pull request against `main`

`CONTRIBUTING.md` describes a contributor equity scheme. Read it there and take
it as what it is: a stated intention by a pre-seed company, not a granted
instrument.

---

## ◈ Security

Report a vulnerability through
[`SECURITY.md`](https://github.com/KyronLabs/kyron/blob/main/SECURITY.md), which
is the one route that is certainly monitored. There has been no external audit.

---

<div align="center">

A subsidiary of **Spidroid Technologies Inc.**

Copyright © 2025 Spidroid Technologies Inc.

</div>
