# 🔮 Mysterious Eastern Force — BaZi Life Blueprint (八字命理)

**Discover your destiny through the ancient Chinese Four Pillars of Destiny.**

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://chimu-z.github.io/bazi-fortune/english/)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> *"Know yourself, know your destiny, know your path."*

## ✨ What is BaZi (八字)?

**BaZi** (八字, "Eight Characters"), also known as the **Four Pillars of Destiny**, is an ancient Chinese metaphysical system with over 2,000 years of history. Unlike Western astrology that maps planetary positions, BaZi analyzes the **Five Elements** (Wood, Fire, Earth, Metal, Water) across your birth year, month, day, and hour to reveal:

- 🎯 **Your Day Master** — Your core personality and life essence
- 🍀 **Your Favorable Element** — What energies support your success
- 🔄 **Major Luck Cycles (大运)** — 10-year life chapter predictions
- ⭐ **Ten Gods (十神)** — Relationship patterns with wealth, authority, and people
- 🔮 **Spirit Stars (神煞)** — Hidden talents and destiny markers
- 💕 **Love & Marriage** — Spouse palace compatibility analysis
- 💰 **Wealth Path** — Financial strengths and wealth accumulation strategy
- 🚀 **Career Direction** — Optimal professional path based on your element

## 🚀 Live Demo

**Try it now:** [https://chimu-z.github.io/bazi-fortune/english/](https://chimu-z.github.io/bazi-fortune/english/)

1. Enter your birth date and hour
2. Get your **free** Four Pillars chart with Five Elements breakdown
3. See your Day Master, Favorable Element, Spirit Stars, and Lucky Elements — **all free**
4. Unlock the complete reading (Major Luck Cycles, 2026 Monthly Forecast, Love, Wealth & Career deep analysis) for **$9.99**

## 🧮 Features

### Free Tier (Instant)
- ✅ Four Pillars (八字) calculation — Year, Month, Day, Hour
- ✅ Five Elements (五行) distribution with visual bars
- ✅ Day Master (日主) analysis with 10 personality profiles
- ✅ Favorable Element (用神) identification
- ✅ Ten Gods (十神) relationship mapping on each pillar
- ✅ Spirit Stars (神煞) — Peach Blossom, Nobleman, Academic Star, Sky Horse, Fortune Star
- ✅ Lucky Elements Guide — colors, numbers, directions
- ✅ Western Zodiac integration

### Premium Tier ($9.99 — One-time, Lifetime Access)
- 🔄 **Major Luck Cycles (大运)** — 8-pillar, 80-year timeline with current cycle highlight
- 📅 **2026 Monthly Breakdown (流月)** — All 12 months with Ten God and star ratings
- 🔮 **Personal Fortune Reading** — Pattern analysis + year forecast
- 💕 **Love & Marriage Analysis** — Spouse palace + compatibility guidance
- 💰 **Wealth Star Analysis** — Financial path + 2026 wealth forecast
- 🚀 **Career & Purpose Reading** — Optimal industries + professional guidance

### Technical Features
- 🌐 Single-file HTML — zero dependencies, instant loading
- 📱 Fully responsive — works on mobile and desktop
- 🔭 Astronomical solar longitude (节气) calculation using IAU formulae
- ✅ Self-verification engine with test cases
- 🌍 SEO optimized — Open Graph, Twitter Cards, JSON-LD structured data
- 💳 Dual payment: Payoneer (card) + Alipay international QR
- 🔗 Referral system — share your reading and earn rewards

## 🏗️ Architecture

```
bazi_english.html (self-contained, ~95KB)
├── CSS (embedded) — Glass-morphism design, CSS custom properties, animations
├── HTML — Form → Results (single-page app, two screens)
└── JavaScript (embedded)
    ├── Astronomy engine — toJD, fromJD, sunLon, solarJD (Newton's method)
    ├── Bazi engine — Four Pillars calculation with 立春 year boundary
    ├── Da Yun engine — Major Luck Cycle calculation (顺排/逆排)
    ├── Shen Sha engine — Spirit Star detection
    ├── Ten Gods engine — Relationship mapping
    ├── Interpretation generators — Fortune, Love, Wealth, Career
    ├── Payment/unlock system — Payoneer + Alipay QR + referral codes
    └── Self-verification — 3 mandatory test cases
```

## 🔬 Accuracy

Our BaZi calculation engine uses:
- **Solar longitude** (太阳黄经): IAU simplified formula (Jean Meeus)
- **Jieqi** (节气): Newton's method iteration for precise solar term dates
- **Year boundary**: 立春 (Lichun, ~Feb 4) — the traditional BaZi year start
- **Month boundary**: 12 solar terms (节) for accurate month pillar assignment
- **Day pillar**: 1900-01-01 = 甲戌日 anchor point
- **Hour pillar**: 五鼠遁 (Five Rat Escape) method

## 📦 Deployment

```bash
# Clone the repo
git clone git@github.com:chimu-z/bazi-fortune.git

# English version
cd bazi-fortune/english/
# Open index.html in browser or deploy to any static host

# Chinese version (with city matching)
# Open index.html in root directory
```

## 🔑 Keywords

`bazi` `four-pillars-of-destiny` `chinese-astrology` `八字` `命理` `fortune-telling` `five-elements` `day-master` `major-luck-cycles` `大运` `十神` `神煞` `feng-shui` `eastern-astrology` `zodiac` `destiny-reading` `chinese-metaphysics` `wu-xing` `heavenly-stems` `earthly-branches`

## ⚠️ Disclaimer

For entertainment purposes only. BaZi readings are based on traditional Chinese metaphysical principles and should not replace professional advice for medical, legal, or financial decisions.

## 📄 License

MIT © 2025 Mysterious Eastern Force
