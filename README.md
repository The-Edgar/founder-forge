# FounderForge

### Zero to Strategy in One Session

> Develop your Business Idea into an actionable strategy based on thorough market research and competitor analysis. Clarify your ICPs, USPs, Pricing, Brand Voice, Website copy and GTM playbook like a YC entrepreneur. Consultant-free.

What takes McKinsey 8 weeks and $200K, FounderForge builds in one session with live market research, battle-tested frameworks, and zero billable hours.


![hero_v3](https://github.com/user-attachments/assets/845777f6-b13f-4ba8-b727-d088847923cb)


---

## What You Get

Six interconnected strategy artifacts with each built through real market research and informed by the one before it:

1. **Ideal Customer Profile**: Know exactly who you're building for. Specific enough to find them on LinkedIn.
2. **Positioning & USPs**: Claim your space in a crowded market. Pass the "only we" test.
3. **Brand Voice Framework**: Sound like you, everywhere, every time. With "this, not that" guardrails.
4. **Service Offerings & Pricing**: Package and price your value. Grounded in market benchmarks.
5. **Website Messaging Map**: Turn visitors into customers. Page-by-page copy frameworks.
6. **GTM Playbook**: Pick your 1-2 channels, get a launch-ready playbook with 4-5 specific hooks per channel.

---

## How It Works

```
Idea → Market Research → Strategic Q&A → 6 Artifacts
        (parallel)        (6-8 questions)   (built sequentially,
                                             each reviewed before
                                             the next begins)
```

1. **Share your business idea**: any stage, any business model
2. **FounderForge researches your market**: competitors, pricing, trends, customer behavior. Live web data, not guesses.
3. **Strategic questions sharpen your positioning**: 6-8 questions across target customer, differentiation, voice, pricing, proof, and scope
4. **Six artifacts are forged one by one**: each presented for your review before the next begins. Prior artifacts feed into subsequent ones.

---

## Quick Start
Add the skill on command line with 
```bash
npx skills add The-Edgar/founder-forge
```
```bash
# Run in Claude Code
/founder-forge Your business idea here
```
OR 
Install as a marketplace plugin.
```bash
# Run in Claude Code

# Step 1: register the marketplace (once per machine)
/plugin marketplace add The-Edgar/founder-forge

# Step 2: install the plugin
/plugin install founder-forge@founder-forge

# Step 3: run it
/founder-forge Your business idea here
```

**Example:**
```
/founder-forge Emergency wildlife removal app for after-hours encounters
/founder-forge AI protocol platform for functional medicine practitioners
/founder-forge Fractional CFO services for Series A startups
```

---

## What Gets Built

Everything lands in `founder-forge-output/`:

```
founder-forge-output/
├── README.md                       ← Overview + table of contents
├── 01-ideal-customer-profile.md
├── 02-positioning-and-usps.md
├── 03-brand-voice-framework.md
├── 04-service-offerings-pricing.md
├── 05-website-messaging-map.md
└── 06-gtm-playbook.md              ← Channel-specific (your chosen channels)
```

---

## Requirements

- **Claude Code or Cowork**
- **Web search tools** (required: FounderForge does real market research)

**Recommended**: [Perplexity MCP server](https://github.com/ppl-ai/modelcontextprotocol) for citation-backed research

**Fallback**: Claude Code's built-in WebSearch

> FounderForge will stop and tell you if search tools aren't available, with setup instructions.

---

## The GTM Hook System

The GTM Playbook goes deeper than "post on LinkedIn." For each of your chosen channels (you pick 1-2), FounderForge:

1. **Researches what's actually working** on that channel in your niche right now
2. **Generates 4-5 specific, ready-to-use hooks**: not templates, but actual copy tailored to your ICP and positioning
3. **Explains why each hook works**: the psychology behind it in one line

Supported channels: Cold Email, LinkedIn, TikTok, Twitter/X, Reddit, YouTube, Partnerships, Communities/Events

---

## Supported Business Types

FounderForge adapts its frameworks based on business type:
- **Service businesses**: Agencies, consultancies, freelancers, coaches
- **SaaS products**: Self-serve, sales-led, or PLG models
- **B2B**: Any company selling to businesses
- **B2C**: Direct-to-consumer brands and services

---

## For Local Testing

```bash
# Clone the repo
git clone https://github.com/The-Edgar/founder-forge
cd founder-forge

# Test locally
claude --plugin-dir .
```

Then in your Claude Code session:
```
/founder-forge [your business idea]
```

---

## Contributing

PRs welcome for:
- Additional channel playbooks
- New reference guides for additional artifact types
- Improvements to existing frameworks
- Bug fixes in the command orchestration

---

## License

MIT: use freely, modify freely, share freely.

