# Mahin and Team — Portfolio Website

A premium, single-file portfolio website for **Mahin and Team** — built with HTML, Tailwind-inspired CSS, and vanilla JavaScript.

---

## 🚀 Run Locally

### Option 1 — Just open the file
```bash
# Double-click index.html in your file manager
# Or open it directly in any modern browser
```

### Option 2 — Local dev server (recommended)
```bash
# Using Python (pre-installed on most systems)
python3 -m http.server 3000
# Then open: http://localhost:3000

# Or using Node.js live-server
npx live-server --port=3000
```

---

## 📁 File Structure

```
mahin-and-team/
├── index.html        ← Complete website (all-in-one)
└── README.md         ← This file
```

All CSS, JS, and HTML are contained in a single `index.html` for maximum portability.

---

## ✨ Features

- **Dark / Light mode toggle**
- **7 Team member cards** (Mahin, Saqib, Toheed, Owais, Sameer, Hasin, Umaid)
- **12 Project cards** with category filtering (Web, AI, Automation, Cloud, App)
- **Project detail modal popup**
- **Stats counter animation** (130+ Projects, 3+ International, 120+ Customers, 4.7 Rating)
- **Sticky navbar** with active section highlighting
- **Scroll reveal animations**
- **Contact form** with success state
- **WhatsApp CTA button**
- **Fully responsive** (mobile + desktop)

---

## 🌐 Deploy to Netlify (Free)

1. Go to [netlify.com](https://netlify.com) → Log in
2. Click **"Add new site"** → **"Deploy manually"**
3. Drag and drop your `index.html` file
4. Done! Your site is live in under 30 seconds.

---

## 🌐 Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# From the project folder
vercel

# Follow the prompts — choose "Other" as framework
```

---

## 🎨 Customization

| What to change | Where in the file |
|---|---|
| Team members | `const teamMembers = [...]` |
| Projects | `const projects = [...]` |
| WhatsApp number | `href="https://wa.me/923000000000"` |
| Email address | `hello@mahinteam.dev` |
| Colors | CSS variables in `:root { ... }` |
| Stats numbers | `data-target="130"` etc. |

---

© 2025 Mahin and Team
