# AI-SEO-Backlink-Ops

> ⚠️ Showcase Only — Core implementation not included.

An operations playbook documenting a structured backlink acquisition campaign for an AI SaaS product. This repository captures the research, submission workflows, tracking tables, and results from a link-building engagement executed during an internship.

---

## Background

Organic backlinks are a primary signal for domain authority and search ranking. This project systematized acquisition across three channels: directory submissions, GitHub community contributions, and vendor cross-linking. The goal was to build a repeatable, low-cost backlink pipeline appropriate for an early-stage AI product.

## Results

| Metric | Value |
|---|---|
| Total backlinks acquired | 30+ |
| Paid spend ceiling (per listing) | $99 |
| Campaign duration | ~1 internship sprint |

Platforms that accepted listings include:

**AI / SaaS directories**
There's An AI For That · Toolify · SaaSHub · AlternativeTo · G2 · Capterra · Futurepedia · TopAI.tools · AI Tools Directory

**General software directories**
Product Hunt · BetaList · Slant · SourceForge · GetApp

## Playbook Structure

```
playbooks/
├── 01-directory-submissions.md   # Free & paid tier tracker
├── 02-product-hunt-launch.md     # Launch day checklist & timeline
├── 03-github-outreach.md         # awesome-* PR strategy
├── 04-vendor-cross-linking.md    # Partner link swap approach
└── 05-tracking-master.md         # Consolidated status table
```

## Channels

### Directory Submissions
Submissions were triaged into three tiers:

| Tier | Cost | Target DA | Notes |
|---|---|---|---|
| Free | $0 | Any | Volume play; submit everywhere |
| Starter paid | $9–$29 | 40+ | Featured listing or do-follow link |
| Premium paid | $49–$99 | 60+ | Selective; ROI-gated |

### Product Hunt Launch
Coordinated launch including hunter outreach, scheduling, upvote mobilization, and post-launch follow-up. The listing itself generates backlinks from PH profile pages and third-party roundups that embed PH data.

### GitHub Awesome-List PRs
Identified `awesome-*` repositories relevant to the product category. Submitted pull requests with concise, well-formatted entries. Acceptance rate: roughly 40% — merged PRs yield high-DA, do-follow backlinks from GitHub.com.

### Vendor Cross-Linking
Mapped integration partners and vendors whose documentation or blog already mentioned similar tools. Reached out to propose mutual mentions or "built with" acknowledgements.

## Methodology Notes

- All submissions used a canonical product description and consistent UTM-tagged URL.
- Backlink status was verified monthly using free-tier ahrefs / Moz checks.
- Paid listings were approved only when the referring domain authority exceeded the cost threshold.

## Status

This is an ops-documentation repository. It contains no application code. The playbooks and tracking tables represent a real campaign and are shared as a reference for similar early-stage growth initiatives.
