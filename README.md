# The Vantage Hub

**Security Knowledge Platform** — A multi-page HTML/CSS prototype for a security intelligence and consultancy platform targeting Indonesia and Asia Pacific markets.

---

## 📁 Project Structure

```
vantage-hub/
├── vantage-hub-complete.html       # 🔗 All-in-one single-page version (SPA)
├── vantage-hub-feed.html           # News & article feed (authenticated)
├── vantage-hub-signup.html         # Registration & onboarding flow
├── vantage-hub-pricing.html        # Pricing tiers & comparison
├── vantage-hub-topics.html         # Explore topics & categories
├── vantage-hub-standards.html      # Security standards library
├── vantage-hub-consultancy.html    # Consultancy advisory page
├── vantage-hub-admin.html          # Admin dashboard
└── README.md
```

---

## 🚀 Pages Overview

| File | Description |
|------|-------------|
| `vantage-hub-complete.html` | Full single-page app combining all views with JS navigation |
| `vantage-hub-feed.html` | Authenticated user feed — articles, trending, bookmarks |
| `vantage-hub-signup.html` | Multi-step sign-up with topic & industry selection |
| `vantage-hub-pricing.html` | Free / Subscribe / Consultancy tiers with billing toggle |
| `vantage-hub-topics.html` | Browse security topics and subtopics |
| `vantage-hub-standards.html` | ISO, NIST, GDPR and other standards reference |
| `vantage-hub-consultancy.html` | Submit advisory questions, track responses |
| `vantage-hub-admin.html` | Admin analytics and content management dashboard |

---

## 🛠️ Tech Stack

- **Pure HTML5 / CSS3 / Vanilla JavaScript** — no frameworks, no build tools required
- **Google Fonts** — Roboto typeface
- **Fully responsive** — mobile, tablet, and desktop layouts
- **No external dependencies** beyond Google Fonts CDN

---

## 🎨 Design System

| Token | Value |
|-------|-------|
| Primary Blue | `#1a73e8` |
| Accent Orange | `#e8510a` |
| Success Green | `#34a853` |
| Text Primary | `#202124` |
| Text Secondary | `#5f6368` |
| Border | `#e8eaed` |
| Background | `#f8f9fa` |

---

## 🌐 How to Run

No build step needed. Just open any HTML file in your browser:

```bash
# Option 1 — Direct open
open vantage-hub-complete.html

# Option 2 — Local server (recommended)
npx serve .
# or
python3 -m http.server 8080
```

Then visit `http://localhost:8080`

---

## 📄 Pages Navigation (Multi-file version)

The individual HTML files link to each other. For the best experience start from:

```
vantage-hub-feed.html        ← Main authenticated experience
vantage-hub-signup.html      ← Onboarding / registration
vantage-hub-pricing.html     ← Landing / pricing
```

For the **all-in-one demo**, use `vantage-hub-complete.html`.

---

## 📌 Notes

- This is a **UI prototype / mockup** — no backend or database is connected
- Advisory content is illustrative only; not a substitute for licensed security services
- Designed primarily for **Indonesian and Asia Pacific** security professionals

---

## 📃 License

MIT License — free to use, modify, and distribute.
