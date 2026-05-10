# The Pipeline Edge — NFL Pick'em 2026

**Walk-Forward Model Validation · 60.0% historical pick'em accuracy over 1,359 games (2021–2025)**

A data-driven, recreational NFL pick'em and confidence pool assistant for weekly selections, weather analysis, and pool tracking.

**[Live Web App](https://thepipelineedge.com)** | **[Privacy Policy](https://thepipelineedge.com/privacy.html)** | **[Terms of Service](https://thepipelineedge.com/terms.html)** | **[GitHub](https://github.com/thepipelineedge/THEPIPELINEEDGE)**

---

## 🎯 Features

### 🤖 Automated Mode
- **Weekly Selections** — Free premium picks posted every Wednesday
- **Weather Tracker** — Live stadium conditions for all 32 teams
- **Lightning Alerts** — Real-time lightning tracking integration
- **Pool Tracker** — Log weekly results and track season performance
- **Season Summary** — Running totals and performance by phase
- **Fan Resources** — Amazon affiliate links for NFL gear

### 🛠️ Manual Backup Mode
- **Game Entry Calculator** — Build confidence scores with adjustments
- **Weekly Pool Builder** — Rank picks 16→1 for your league
- **Score Reference** — Confidence tier system (1–14 hard cap)
- **Injury Reference** — Tier classification for injury impact
- **Referee Lookup** — Crew adjustment data (+2 to −2)
- **Luck Flags** — 2026 team luck analysis (regress/bounce)
- **Model Validation** — Historical walk-forward test results (2021–2025)
- **Stadium Data** — All 32 NFL stadiums with dome/outdoor classification

---

## 📊 Model Performance

Walk-forward model validation across 1,359 historical NFL games (2021–2025):

| Year | Accuracy | Record |
|------|----------|--------|
| 2025 | 62.4% | In progress |
| 2024 | 65.1% | 177/272 |
| 2023 | 57.0% | — |
| 2022 | 59.2% | — |
| 2021 | 57.8% | — |
| **Overall** | **60.0%** | **1,359 games** |

**Methodology:** The model blends 6 different prediction algorithms trained on historical play-by-play data, team strength metrics, and advanced statistics. Results provided for informational purposes only and do not guarantee future outcomes.

---

## ⚠️ Entertainment Only

**This app is for entertainment and recreational pool use only. It is NOT a betting or gambling app.**

- ✅ No real-money gambling features
- ✅ No sportsbook integration
- ✅ No betting advice or odds
- ✅ No guarantees on predictions

Weekly selections, confidence rankings, model ratings, and stats are for informational purposes only and do not guarantee future outcomes.

---

## 🔒 Privacy & Data

### Data Stored Locally
All data is stored **only on your device** in your browser. We never send this to our servers or any other company:
- Weekly pick selections and confidence scores
- Pool results (wins, losses, points each week)
- Season performance history
- Game notes and preferences

**You control this data:** Clear your browser cache anytime to delete everything permanently.

### Optional Features
When you use optional features (weather, lightning tracking), we send:
- Stadium latitude/longitude coordinates (public information)
- **NO personal data** — no names, emails, device IDs, or personal identifiers

### Third-Party Services
- **Open-Meteo** (openmeteo.com) — Real-time weather data for outdoor stadiums
- **LightningMaps.org** — Real-time lightning tracking near game venues

Both features are completely optional. The app works 100% offline without them.

---

## 💰 Refunds & Money Back Guarantee

**All refunds are managed exclusively by Google Play Store, not by The Pipeline Edge.**

### Refund Policy:
- **Refund Window:** 48 hours from purchase
- **How to Request:** Open Google Play Store → Manage Purchases → Select The Pipeline Edge → Request Refund
- **Processing:** Google Play processes refunds per their standard policy
- **Limitations:** We cannot manually process refunds or extend the refund window
- **Support:** For refund issues, contact Google Play Store support directly

### Important Notes:
- You are fully responsible for any decisions made using this app
- Refunds are subject to Google Play Store's refund policies
- We cannot process refunds manually or bypass the 48-hour window
- For all refund inquiries, contact Google Play Store support directly

---

## 🆘 Gambling Support

If you struggle with gambling, help is available:

- 🇺🇸 **US:** [1-800-GAMBLER](https://www.ncpgambling.org) (ncpgambling.org)
- 🇬🇧 **UK:** [0808 8020 133](https://www.begambleaware.org) (begambleaware.org)
- 🇦🇺 **Australia:** [1800 858 858](https://www.gamblinghelponline.org.au) (gamblinghelponline.org.au)

---

## 📱 Platforms

- ✅ **Web** — Fully responsive, mobile-friendly
- 🔨 **Android** — Building AAB file for Google Play
- 🍎 **iOS** — Building IPA file (Mac required)

---

## 🌐 Live Web App

Visit **[https://thepipelineedge.com](https://thepipelineedge.com)** to use The Pipeline right now!

**Features:**
- ✅ **English/Spanish toggle** in header
- ✅ **Offline mode** — works without internet
- ✅ **Mobile responsive** — optimized for phones, tablets, desktop
- ✅ **localStorage** — automatic save of picks and pool results
- ✅ No download needed, no account required

---

## 📋 File Structure

```
THEPIPELINEEDGE/
├── index.html          # Main app (2,587 lines)
├── privacy.html        # Privacy Policy
├── terms.html          # Terms of Service
├── README.md           # This file
└── .gitignore         # Git ignore rules
```

---

## 🏈 Confidence Score System

**Base Layer (Blend Differential):** 1–10 points
- Derived from team strength metrics and matchup analysis

**Model Consensus:** −2 to +2 points
- 4–6 models agree = 0
- 5–6 models agree = +1
- All 6 models agree = +2

**Referee Adjustment:** −1 to +1 points
- Crew tendencies (home/road favoritism)

**Injury Filter:** −2 to 0 points
- Tier 1: No impact = 0
- Tier 2: Role player = −1
- Tier 2.5: Starting skill player = −1.5
- Tier 3: Elite player = DROP

**Luck Factor:** −1 to +1 points
- Team regression/bounce-back analysis

**Final Score (Hard Cap):** 1–14 points

---

## 🎮 How It Works

### Step 1: Enter Game Details
- Select Away Team & Home Team
- Input Blend Differential (team strength edge)
- Select Model Agreement (how many models agree)

### Step 2: Apply Adjustments
- Injury Filter (tier classification)
- Referee Adjustment (crew tendencies)
- Luck Factor (regression/bounce analysis)

### Step 3: Get Confidence Score
- Automatic calculation (1–14 hard cap)
- Color-coded tiers (green/blue/amber/red)

### Step 4: Build Your Pool
- Add picks to weekly pool
- Auto-rank by confidence
- Save to localStorage

### Step 5: Track Results
- Log weekly wins/losses/points
- View season summary
- Track performance by phase

---

## 🚀 Deployment

- **Website:** [https://thepipelineedge.com](https://thepipelineedge.com)
- **Hosting:** Cloudflare Pages (auto-deploy from GitHub)
- **GitHub:** [https://github.com/thepipelineedge/THEPIPELINEEDGE](https://github.com/thepipelineedge/THEPIPELINEEDGE)

### Auto-Deploy Workflow
1. Push changes to GitHub
2. Cloudflare automatically detects changes
3. Builds and deploys the live site
4. Live in seconds! ⚡

---

## 🤝 Support

For issues, questions, or feedback:
1. Check the in-app help sections
2. Review injury/ref/luck reference tables
3. Test with sample picks (load test data button)
4. Email: **thepipelineedge@gmail.com**

---

## 📄 Legal

**© 2026 The Pipeline Edge. All rights reserved.**

- [Privacy Policy](https://thepipelineedge.com/privacy.html)
- [Terms of Service](https://thepipelineedge.com/terms.html)

Entertainment purposes only. No guarantees on predictions. User assumes all responsibility for decisions made using this app.

---

**Good luck. The work is done. Trust the system. 🏈**
