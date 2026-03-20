# 🛡️ GigGuard — Earn Even When You Can't Work

> **Insurance + Community Savings + Personal Savings — all in one ₹50/week plan**  
> Built for DEV Trails University Hackathon 2026 · In partnership with EY

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Now-1e6fff?style=for-the-badge)](https://Bhavani3010.github.io/gigguard-ai/)
[![Built With](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-ff6b2b?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-00d68f?style=for-the-badge)](#)

---

## 🚨 The Problem

India has **15+ million delivery partners** on platforms like Swiggy and Zomato. They earn only when they work.

But during **heavy rain, floods, extreme heat, or pollution** — they cannot go out and deliver.

> **No work = No income.** Yet bills don't stop.

Existing insurance systems:
- ❌ Don't cover daily income loss
- ❌ Require manual claims and long waiting periods
- ❌ Make riders feel their premium is wasted if nothing happens

---

## 💡 The Solution — GigGuard

GigGuard **is** insurance — but a smarter, fairer kind called **Parametric Microinsurance**, combined with a community savings model.

Every ₹50 weekly premium is split into **3 parts that each serve a different purpose**:

| Pool | Amount | What it is | What it does |
|---|---|---|---|
| 🛡️ **Risk Pool** | ₹30 (60%) | **Parametric Insurance** | Automatically pays riders when weather is unsafe |
| 🤝 **Community Fund** | ₹10 (20%) | **SHG Mutual Aid** | Emergency backup + micro-loans for the community |
| 💰 **Savings Pool** | ₹10 (20%) | **Personal Savings** | Always yours — withdraw anytime, never lost |

> **The genius:** If weather is bad → Risk Pool pays you. If nothing happens → Savings Pool pays you back. Every rupee works for the rider.

### One Line: *Riders get paid automatically when they can't work — and never lose their premium money.*

---

## ⚙️ How It Works

```
Rider pays ₹50/week
        ↓
Split into 3 pools:
  🛡️ ₹30 (60%) → Risk Pool      ← parametric insurance, funds payouts
  🤝 ₹10 (20%) → Community Fund  ← SHG mutual aid, emergency backup
  💰 ₹10 (20%) → Savings Pool    ← personal savings, withdraw anytime
        ↓
IMD monitors hyperlocal weather every 15 minutes per pincode
        ↓
AI calculates Workability Score per zone
        ↓
Score drops below threshold → 3 fraud checks run automatically
  ✅ Was rider active on platform before disruption?
  ✅ GPS — Was rider in the affected zone?
  ✅ Matches rider's normal work pattern?
        ↓
Dynamic Payout = Risk Pool ÷ Affected Riders (₹80–₹300 range)
        ↓
💸 Money credited in ~12 seconds. WhatsApp alert sent.
```

---

## 🌟 Key Features

| Feature | Description |
|---|---|
| ⚡ **Zero-Claim Payout** | No forms, no calls — money arrives automatically |
| 🧮 **Dynamic Formula** | Risk Pool ÷ Affected Riders = fair, live calculation |
| 📍 **Hyperlocal Zones** | Rain in Adyar ≠ payout for riders in Anna Nagar |
| 🔍 **3 Fraud Checks** | Platform activity + GPS + work pattern verification |
| 💰 **Savings Withdraw** | Your savings pool is always yours — withdraw anytime |
| 🆘 **Safety Pause** | Press a button to pause — system verifies and compensates |
| 🔥 **Streak Rewards** | Consistent payers get loyalty bonuses |

---

## 💰 Money Flow (100 Riders Example)

```
Weekly collection:  100 riders × ₹50 = ₹5,000
                                          │
                    ┌─────────────────────┼──────────────────────┐
                    ▼                     ▼                      ▼
             🛡️ Risk Pool          🤝 Community Fund       💰 Savings Pool
               ₹3,000 (60%)          ₹1,000 (20%)           ₹1,000 (20%)
           Parametric Insurance    SHG Mutual Aid         Personal Savings
            Pays disruptions       Emergency backup       Withdraw anytime

Heavy Rain Week — 30 riders affected:
  Payout = ₹3,000 ÷ 30 = ₹100/rider (auto-credited, no claim needed)

Clear Week — 0 riders affected:
  All 100 riders → ₹10 each added to personal savings → withdraw anytime
```

---

## 🗺️ Hyperlocal Zone System

GigGuard uses **India Meteorological Department (IMD)** data polled every 15 minutes per pincode — not city-wide averages.

9 zones tracked in Chennai alone:
`Adyar · T.Nagar · Velachery · Anna Nagar · Tambaram · Porur · Guindy · Mylapore · Sholinganallur`

Only riders in **actually affected zones** get payouts. Others accumulate savings. 🎯

---

## 🖥️ Demo Pages

| Page | Description |
|---|---|
| [🏠 Landing](index.html) | Product overview, how it works, money flow |
| [📝 Onboarding](onboarding.html) | 5-step rider registration with payment setup |
| [📊 Dashboard](dashboard.html) | Live workability score, pools, safety pause |
| [⚡ Simulation](simulation.html) | Live demo — trigger rain/heat/flood, watch auto-payout |
| [📋 History](history.html) | Transaction history, cashback tracker, pool health |

---

## 🛠️ Tech Stack

- **Frontend:** Pure HTML5, CSS3, JavaScript (no frameworks — fully offline-capable)
- **Data:** Simulated IMD weather API integration
- **Storage:** localStorage for rider session persistence
- **Fonts:** Syne (display) + DM Sans (body) via Google Fonts
- **Design:** Dark UI, glassmorphism cards, CSS animations

---

## 🚀 Run Locally

```bash
git clone https://github.com/Bhavani3010/gigguard-ai.git
cd gigguard-ai
# Open index.html in any browser — no server needed!
```

---

## 📋 Hackathon Submission Details

**Event:** DEV Trails University Hackathon · Seed Phase  
**Theme:** Fintech / Social Impact / AI  
**Team:** Bhavani  , Adishree , Monica
**Track:** AI-powered financial inclusion for gig workers

### What Makes This Different
- 🛡️ **Parametric microinsurance** — payout triggers automatically on weather condition, not manual claim
- 🤝 **SHG community fund** — riders back each other up, inspired by India's Self Help Groups
- 💰 **Personal savings built in** — 20% of every premium is personal savings, always withdrawable
- 📍 **Hyperlocal** — pincode-level precision, not city-wide blunt payouts
- 🔁 **Premium never wasted** — either you get a payout OR your savings come back to you

---

## 🔮 What's Next

- [ ] Real IMD API integration
- [ ] Swiggy/Zomato earnings API for auto-deduction
- [ ] WhatsApp bot interface for low-tech riders
- [ ] PMSBY/PMJJBY government scheme linkage
- [ ] Expand to 50+ cities across India

---

## 📄 License

MIT License — free to use, build on, and improve.

---

<div align="center">

**Built with ❤️ for India's 15 million delivery heroes**

*GigGuard — Because rain shouldn't mean hunger.*

</div>
