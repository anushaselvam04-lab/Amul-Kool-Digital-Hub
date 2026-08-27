# 🥛 Amul Kool Elaichi - Interactive 3D Web Experience

An interactive, responsive product experience celebrating India's iconic **Amul Kool Elaichi** flavoured milk. Featuring a 240-frame dynamic fluid simulation canvas, interactive nutrition calculator, flavour carousel, mixology recipes, store locator modal, and harmonic Web Audio API chimes.

---

## ✨ Key Features

- **240-Frame Fluid Simulation Canvas**:
  - Auto-play with smooth 30fps rendering and nearest-frame fallback smoothing.
  - Interactive controller bar with Play/Pause, jump milestones (*Start, Splash, Crown, End*), live frame counter (`F: 001/240`), and timeline range scrubber.
  - Mouse drag and touch swipe directly on the canvas to scrub smoothly through the pour.
- **Interactive Nutrition Calculator**:
  - Live toggle between **Per 100ml** and **Per 200ml Bottle** servings with dynamic recalculation of Calories, Fat, Protein, Carbs, and Calcium.
- **Product Range & Mixology**:
  - Flavour cards for *Elaichi, Kesar, Badam, and Rose*.
  - Step-by-step recipe inspirations (*Falooda Shake, Matka Kulfi, Cardamom Chia Bowl*).
- **Store Locator & Instant Delivery Modal**:
  - Quick pincode search simulation and one-click redirect links to **Blinkit**, **Zepto**, **Swiggy Instamart**, and **Amul Online**.
- **Web Audio API**:
  - Synthesized refreshing ambient chime on audio button toggle or pressing <kbd>M</kbd>.
- **Keyboard Shortcuts**:
  - <kbd>Space</kbd> : Toggle Play / Pause
  - <kbd>←</kbd> / <kbd>→</kbd> : Step frame backward / forward
  - <kbd>M</kbd> : Play ambient chime
  - <kbd>Esc</kbd> : Close open modal

---

## 🚀 Deploying to Vercel

This project is structured for **zero-config static deployment** on [Vercel](https://vercel.com).

### Method 1: Deploy with Vercel Web Dashboard (Recommended)
1. Push this repository to GitHub: `https://github.com/anushaselvam04-lab/Amul-Kool-Digital-Hub.git`
2. Go to **[vercel.com/new](https://vercel.com/new)** and connect your GitHub account.
3. Select **Amul-Kool-Digital-Hub** repository.
4. Keep the default settings (Framework Preset: *Other*, Root Directory: `./`).
5. Click **Deploy**. Your website will be live in under 30 seconds with automated SSL, global edge CDN, and asset caching configured via `vercel.json`.

### Method 2: Deploy with Vercel CLI
```bash
npm i -g vercel
vercel
```

---

## 💻 Running Locally

You can serve the website with any static web server:

**Using Python:**
```bash
python -m http.server 8000
```
Open [http://localhost:8000](http://localhost:8000) in your web browser.

---

## 🛠️ Built With

- **HTML5 & Canvas 2D API** - Dynamic high-performance frame rendering
- **Tailwind CSS (CDN)** - Modern styling, gradients, and glassmorphism UI
- **Google Fonts** - *Plus Jakarta Sans* & *Cabinet Grotesk*
- **Google Material Symbols** - Modern icon library
- **Web Audio API** - Native browser oscillator synthesis for ambient audio
- **Vercel** - Global edge hosting & static asset optimization
