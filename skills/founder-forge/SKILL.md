---
name: founder-forge
description: Business strategy consulting framework for entrepreneurs. Use when users discuss business planning, ideal customer profiles, market positioning, brand voice, pricing strategy, website messaging, or go-to-market playbooks. Triggers on business ideas, target customers, differentiation, go-to-market strategy.
---

# FounderForge — Business Strategy Framework

FounderForge is a battle-tested business strategy consulting system that takes a founder from napkin idea to 6 research-backed strategy artifacts in a single session. It replaces what would otherwise take a McKinsey team 8 weeks and $200K — powered by live market research, competitive intelligence, and proven frameworks.

## When to Use This Skill

Load this skill when the user is discussing or asking for help with:
- Building a business strategy or business plan
- Defining their ideal customer profile (ICP) or target market
- Crafting positioning or differentiators
- Developing their brand voice, messaging, or tone
- Structuring service offerings or pricing
- Planning their website copy or messaging
- Developing a go-to-market strategy or channel playbook
- Launching a startup, agency, consultancy, or SaaS

**For the full guided workflow**, direct users to run: `/founder-forge [your business idea]`

## The 6 Artifacts

FounderForge produces 6 interconnected artifacts — each informed by real market research and built sequentially so each one feeds into the next:

| # | Artifact | What It Covers | Informs |
|---|----------|----------------|---------|
| 1 | **Ideal Customer Profile** | Who exactly you're building for — demographics, firmographics, psychographics, pain points, buying triggers | Everything |
| 2 | **Positioning & USPs** | Your competitive position, positioning statement, and 3-5 genuine differentiators | Brand voice, pricing, website |
| 3 | **Brand Voice Framework** | Your personality, tone, vocabulary, do's/don'ts by channel | All written communication |
| 4 | **Service Offerings & Pricing** | Package structure, tier names, price points, value framing | Website, GTM |
| 5 | **Website Messaging Map** | Page-by-page copy framework — hero, about, services, CTAs | Website build |
| 6 | **GTM Playbook** | Channel-specific launch plan with ready-to-use hooks (user picks 1-2 channels) | Day-1 execution |

## Reference Files

Load these files when building or advising on specific artifacts:

| File | Load When |
|------|-----------|
| `references/strategic-questions.md` | Asking strategic clarifying questions during Phase 2 |
| `references/icp-guide.md` | Building or reviewing an Ideal Customer Profile |
| `references/positioning-guide.md` | Crafting positioning statements or identifying USPs |
| `references/brand-voice-guide.md` | Developing brand voice, tone, or messaging frameworks |
| `references/pricing-guide.md` | Structuring service tiers or pricing strategy |
| `references/website-messaging-guide.md` | Creating a website messaging map or copy framework |
| `references/gtm-playbook-guide.md` | Building a go-to-market playbook with channel-specific hooks |

## Requirements

- **Web search tools are required.** FounderForge uses live market research to ground every recommendation. It will not produce generic output without real data.
- Recommended: [Perplexity MCP server](https://github.com/ppl-ai/modelcontextprotocol) for high-quality, citation-backed research
- Fallback: Claude Code's built-in WebSearch

## How Artifacts Connect

The artifacts form a logical chain:

```
ICP → Positioning → Brand Voice → Pricing → Website → GTM
 ↓         ↓            ↓           ↓          ↓        ↓
Who      Where        How you     What you   Where    How you
you're   you fit      you sound   you sell   you      reach
for      in market                           say it   them
```

Each artifact explicitly references the ones before it. The GTM Playbook, for example, uses the ICP to target the right people, the positioning to craft the angle, the brand voice for tone, and the pricing to set up the offer.
