# 📸 Magic Today Photography ― Bangalore’s Finest Wedding Photography Company

[![Website Online](https://img.shields.io/badge/live-demo-green?style=for-the-badge&logo=vercel)](https://magictodayphotography.vercel.app)
[![Deployed with Vercel](https://img.shields.io/badge/deploy-vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com)
![Static Build](https://img.shields.io/badge/static-site-orange?style=for-the-badge&logo=html5)
![MIT License](https://img.shields.io/github/license/Kirankumarvel/magictodayphotography?color=blue&style=for-the-badge)

---

> 👋 **Welcome!**  
> This is the single‑file, 100% static, SEO‑focused website for Magic Today Photography ―  
> *Wedding, pre-wedding, event, newborn, and maternity photography specialists in Bangalore, India.*

---

## ✨ Live Demo

**🌐 [magictodayphotography.vercel.app](https://magictodayphotography.vercel.app)**

---

## 🎯 Project Overview

Magic Today Photography’s website is:

- **Single page. Fully responsive. Zero build or dependencies.**
- Designed for strong Google ranking for top Bangalore photographer & wedding keywords.
- Features a modern, dark-gold aesthetic, customizable WhatsApp integration, floating chat, local business schema, animations, and more.
- 🚀 *Perfect for instant deployment on [Vercel](https://vercel.com)!*

---

## 🔥 Features At a Glance

| Feature                         | Details                                                                             |
|----------------------------------|-------------------------------------------------------------------------------------|
| **💡 Static Site**              | No Node.js, no build step, no dependencies (CDNs only)                              |
| **📱 Responsive**               | Mobile-first, fluid scaling                                                         |
| **🚀 Ultra SEO**                | Rich meta tags, JSON-LD LocalBusiness, FAQPage schema                               |
| **🎨 Elegant Animations**       | GSAP & ScrollTrigger (CDN), bokeh effect, animated counters                         |
| **🥇 WhatsApp Chat Widget**     | Floating fixed button, service prefill, fully customizable                          |
| **📝 Contact Form**             | Integrated with [Formspree](https://formspree.io) (free, no backend needed)         |
| **📍 Google Maps Ready**        | Address + schema to improve local search ranking                                    |
| **🖼️ Unsplash Images**         | Replace with your own at any time                                                   |
| **⚡ Performance**              | Only essential external assets, lazy images, compressed CSS & JS                    |
| **🔑 100% Ownable**             | Edit absolutely everything in one HTML file!                                        |

---

## 🛠️ Tech Stack At-a-Glance

| 🔗 Stack Element       | Purpose                                              |
|-----------------------|------------------------------------------------------|
| **HTML5**             | Structure & content                                  |
| **CSS3**              | Styling, responsive design, custom animations        |
| **Vanilla JS**        | Interactions, effects, counters, WhatsApp widget     |
| **GSAP + ScrollTrigger** | Modern scroll animations (from CDN)               |
| **Font Awesome 6**    | SVG icons (from CDN)                                 |
| **Google Fonts**      | Typography                                           |
| **Formspree.io**      | Serverless contact form                              |
| **Vercel**            | Fast, free, zero-config deployment                   |

---

## 🗂️ Project Structure

```
/
├── index.html           # The entire site ― HTML, CSS & JS in one!
├── README.md            # You're reading it!
└── vercel.json          # (optional) Only needed for SPA-style deep linking
```

<details>
<summary><strong>Click to see an Example <code>vercel.json</code> for SPA routing</strong></summary>

```json name=vercel.json
{
  "rewrites": [{ "source": "/(.*)", "destination": "/index.html" }]
}
```
</details>

> Images are hotlinked from Unsplash.  
> _**Tip:** Replace with your own for personalization or copyright reasons._

---

## ⚡ Fast Deployment (Vercel Recommended)

<details>
<summary><strong>📦 Deploy Option A: Drag & Drop (No Git required)</strong></summary>

1. Visit [vercel.com](https://vercel.com) → sign up (free).
2. Click **“Deploy”** → “Drag and Drop”.
3. Drop your `index.html` file.
4. Done! Vercel auto-assigns a public URL.

</details>

<details>
<summary>📦 <strong>Deploy Option B: GitHub & Vercel (Recommended for Version Control)</strong></summary>

1. Create this repo on GitHub, upload `index.html` (& optional `vercel.json`).
2. On Vercel, click “New Project” → Import your repo.
3. Click **Deploy**.  
   Every push to `main` triggers an instant redeploy.
</details>

> **Note:** [`vercel.json`](#project-structure) is only required for SPA-style routing (if you use e.g. `/about` routes, not for standard anchor use like `#about`).

---

## 🏆 SEO & Keyword Focus

**Targeted keywords and their placements:**

| Keyword                           | Placement Example                  |
|------------------------------------|------------------------------------|
| `wedding photographer bangalore`   | H1, meta desc, about, footer       |
| `pre wedding shoot bangalore`      | Services, FAQ, pricing             |
| `candid wedding photography bangalore` | Hero H1, testimonials         |
| `newborn photographer bangalore`   | Services, FAQ, about               |
| `event photographer bangalore`     | Service section, testimonials      |
| `maternity photoshoot bangalore`   | Service & reviews, FAQ             |
| `photographer in banashankari`     | Studio address (editable)          |

> 🪧 **After deploy:** Submit your site to [Google Search Console](https://search.google.com/search-console/about) and request indexing!

---

## 🎛️ Customization Guide

- ✏️ **Text/Services:** Edit everything in `<body>` in `index.html`
- 📷 **Images:** Replace Unsplash URLs in `<img>` tags with your own
- 📞 **Contact Info:** Find `+91  80957 67131` and `info.magictoday@gmail.com` and replace in the code
- 🟢 **WhatsApp:** Global search for ` 80957 67131` (without `+`), and replace with your number
- 📝 **Contact Form:** Formspree endpoint is `https://formspree.io/f/info.magictoday@gmail.com`. For your own email, [set up a Formspree account](https://formspree.io).

---

## 💬 WhatsApp Service Widget

- 🌟 Floating button (bottom right), opens services picker → “Start Chat” prefills message to WhatsApp (`+91 80957 67131` by default)
- ✨ **Edit number easily:** Modify inside `<script>` – search for `waSend`

---

## 📨 Contact Form

- Fully integrated **Formspree** (free tier: 50 submissions/month)
- Endpoint currently:  
  `https://formspree.io/f/info.magictoday@gmail.com`
- Swap to your own by creating a [Formspree](https://formspree.io) account.

---

## 🧪 Local Testing

```ansi
npx serve .
```

Or simply open `index.html` in any browser.  
(For best results & scroll animations, use Live Server in VS Code, or serve over localhost.)

---

## 🏷️ License

MIT License © [Kirankumarvel](https://github.com/Kirankumarvel)  
*Free for all personal, commercial or client photography sites. Attribution appreciated, but not required.*

---

## 🙏 Credits

- [Unsplash](https://unsplash.com/) — Demo photos
- [GSAP](https://gsap.com/) — Animations and scroll effects
- [Font Awesome](https://fontawesome.com/) — Icons
- [Formspree](https://formspree.io/) — Form backend

---

## ❓ Need Help?

- Open a [GitHub Issue](https://github.com/Kirankumarvel/magictodayphotography/issues)  
- Email: `info.magictoday@gmail.com`

---

> _🚀 Launch your site on Vercel and watch it rank for wedding photography in Bangalore and beyond!_
