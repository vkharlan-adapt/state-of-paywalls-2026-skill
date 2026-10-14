# State of Paywalls 2026 by Adapty: Claude Skill

Ask Claude about paywall benchmarks instead of reading the report.

This skill gives Claude the full [State of Paywalls 2026](https://adapty.io/state-of-paywalls-2026/) report by [Adapty](https://adapty.io): 78,000+ paywalls from 30,000+ App Store apps, October 2025 to September 2026, across 5 regions (US, Europe, APAC, LATAM, MEA) and 8 categories.

## What you can ask

- **Benchmark your numbers.** "My Health & Fitness app sells mostly in Europe. 21% of trials convert to paid. How do I compare?"
- **Check your pricing.** "What do Productivity apps charge for an annual plan in LATAM?"
- **Audit your paywall.** Send a screenshot and ask "What would you change?" Claude compares it element by element with the 100 top paywalls, checks it against conversion data, and ranks the next 3 tests.
- **Find your next test.** "Our trial starts are low. What should we test first?"

Claude answers with medians, the middle 50% of apps and the top 10% for your region, category and plan length.

## What's inside

- All five chapters: baseline, pricing & packaging, paywall design, placement & timing, testing & personalization
- Chart data: view → paid, view → trial and trial → paid conversion, plus prices, by region × category × plan
- Revenue mix, pre-selection, lifetime plans, trial length, discounts, cancellations, second-chance paywalls, A/B test win rates and lifts

## Install

### Claude.ai (web, desktop)

1. Download [`state-of-paywalls-2026-by-adapty.zip`](https://github.com/vkharlan-adapt/state-of-paywalls-2026-skill/raw/main/state-of-paywalls-2026-by-adapty.zip).
2. In Claude, go to **Customize > Skills**.
3. Click **+**, then **Create skill**, then **Upload a skill**, and select the ZIP.

Skills need **Code execution and file creation** turned on under **Settings > Capabilities**.

### Claude Code

```bash
git clone https://github.com/vkharlan-adapt/state-of-paywalls-2026-skill.git ~/.claude/skills/state-of-paywalls-2026-by-adapty
```

## Methodology

App Store data only. Benchmarks are calculated app by app, shown only when at least 20 apps qualify. Revenue in USD after refunds, before store fees; European prices include VAT. The paywall design chapter is a manual review of 100 top iOS paywalls (Mobbin screenshots), so it describes patterns, not conversion impact. Full methodology is in the [report](https://adapty.io/state-of-paywalls-2026/).

## About Adapty

[Adapty](https://adapty.io) helps subscription apps grow revenue: build paywalls and onboarding flows without code, A/B test them, and target them by country, user attributes or acquisition source, all without an app release.
