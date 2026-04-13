# 🧠 NutriMind

**Smart Diet for Mental Wellness** — AI-powered nutrition intelligence that maps food to your mood, biomarkers, and biology.

![NutriMind](https://img.shields.io/badge/NutriMind-v1.0-00c6a2?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Deploy](https://img.shields.io/badge/deploy-GitHub%20Pages-blue?style=flat-square)

---

## 🌐 Live Demo

**[→ Visit NutriMind](https://YOUR_USERNAME.github.io/nutrimind)**

---

## ✨ Features

- 🎯 **Mood-to-Food Engine** — 47+ foods scientifically scored against 6 mental states
- 🔬 **Biomarker Tracking** — Vitamin D, B12, Omega-3, Iron, Magnesium, and more
- ⚠️ **Drug Interactions** — Flag dangerous food-drug combinations (MAOIs, warfarin, statins)
- 📅 **Daily Meal Plans** — Personalised breakfast, lunch, dinner & snack timelines
- 📚 **Evidence-Based** — Every recommendation cites peer-reviewed research
- 👨‍🍳 **Step-by-Step Recipes** — Preparation tips for maximum nutrient retention
- 🧬 **TDEE Calculation** — Caloric needs based on your biometrics

---

## 🏗️ Project Structure

```
nutrimind/
├── index.html       # Landing / main page
├── app.html         # Full app (onboarding → dashboard)
├── README.md
├── .gitignore
└── .github/
    └── workflows/
        └── deploy.yml   # Auto-deploy to GitHub Pages
```

---

## 🚀 Deploy to GitHub Pages (5 minutes)

### Option A — Automatic (recommended)

1. **Fork or push** this repo to your GitHub account
2. Go to **Settings → Pages**
3. Set source to **GitHub Actions**
4. Push any commit — the workflow auto-deploys!

### Option B — Manual branch deploy

1. Push to GitHub
2. Go to **Settings → Pages**
3. Set source branch to `main`, folder to `/ (root)`
4. Your site is live at `https://YOUR_USERNAME.github.io/nutrimind`

### Option C — Netlify (instant)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start)

1. Drag the `nutrimind/` folder into [netlify.com/drop](https://app.netlify.com/drop)
2. Done. Instant live URL.

### Option D — Vercel

```bash
npm i -g vercel
cd nutrimind
vercel --prod
```

---

## 💻 Local Development

No build step required — pure HTML/CSS/JS.

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/nutrimind.git
cd nutrimind

# Option 1: Python
python3 -m http.server 8080

# Option 2: Node
npx serve .

# Option 3: VS Code
# Install "Live Server" extension → right-click index.html → Open with Live Server
```

Then open [http://localhost:8080](http://localhost:8080)

---

## 🔬 Science Behind NutriMind

NutriMind synthesises research from nutritional psychiatry, including:

- **Gut-Brain Axis** — How gut microbiome affects neurotransmitter production
- **Serotonin Synthesis** — Tryptophan-rich foods and co-factors (B6, zinc)
- **Neuroplasticity** — BDNF-boosting foods (blueberries, omega-3s)
- **Inflammation Pathways** — Anti-inflammatory diet patterns for mood stability
- **Dopamine Precursors** — Tyrosine-rich foods for motivation and focus

---

## ⚠️ Disclaimer

NutriMind is an **educational tool** for general wellness information. It does **not** replace professional medical or nutritional advice. Always consult a qualified healthcare provider before making significant dietary changes, especially if you have medical conditions or take medications.

---

## 📄 License

MIT © 2025 NutriMind
