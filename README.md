# Koretechsolutions
# Kore Tech Solutions — Website

A single-file, fully responsive landing page for **Kore Tech Solutions**, built by Chandrakant Shivaji Kore. Showcases services, business solutions, founder profile, projects, certifications, and contact details.

**File:** `kore-tech-solutions.html`
No build tools, no dependencies to install — just open the file or upload it anywhere.

---

## ✨ Features

- **Responsive design** — works cleanly on mobile, tablet, and desktop (fluid typography + breakpoints from 320px up to large screens)
- **Mobile navigation** — hamburger menu with slide-in drawer on small screens
- **Sticky mobile CTA bar** — WhatsApp + Email quick actions fixed to the bottom on phones
- **Scroll animations** — sections and cards fade in as you scroll (respects `prefers-reduced-motion`)
- **Animated hero terminal** — a styled code/terminal visual representing the brand
- **Founder section** — embedded profile photo, bio, animated skill bars, and links to CV/portfolio/socials
- **Projects grid** — 8 projects pulled from the live portfolio, each linking out
- **Certifications grid** — 5 certifications with direct certificate links
- **Working email flow** — tapping any email link copies the address to clipboard (with a toast confirmation), since `mailto:` alone doesn't work on phones without a configured mail app
- **Back-to-top button** — appears after scrolling
- **Self-contained** — the founder photo is embedded as base64, so the file has zero external image dependencies

---

## 🗂 Sections (in order)

1. **Nav** — sticky header with logo + links (Services, Solutions, Founder, Contact)
2. **Hero** — headline, tagline, WhatsApp/Email CTAs, animated terminal
3. **Trust bar** — Quality / Student Budget / On-Time / Support
4. **Services** (`#services`) — Web, Python, Java, Database, Management Systems, Custom Solutions
5. **Solutions that grow your business** (`#growth`) — Digital Presence, Automation, Data Management, Efficiency, Growth
6. **Why Choose Us + Stack** (`#stack`)
7. **Founder** (`#founder`) — profile, skills, projects, certifications, extracurricular
8. **Quote band** — brand tagline
9. **Contact** (`#contact`) — Email, WhatsApp, Instagram, LinkedIn cards
10. **Footer** — final CTA + social links

---

## 🚀 How to deploy (publish a live link)

### Option 1 — GitHub Pages (free, recommended)
1. Create a new repo on GitHub, e.g. `kore-tech-solutions`
2. Upload `kore-tech-solutions.html` to the repo and **rename it to `index.html`**
3. Go to repo **Settings → Pages**
4. Under "Source," select the `main` branch → Save
5. Your live link will be:
   `https://chandrakantkore.github.io/kore-tech-solutions/`

### Option 2 — Netlify Drop (fastest, no account needed)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the HTML file into the browser
3. Get an instant live link (e.g. `something.netlify.app`)
4. Optional: create a free account to customize the subdomain

### Option 3 — Vercel
Similar flow to Netlify; connect a GitHub repo for automatic redeploys on every push.

---

## 🛠 How to customize

Everything is in one file — open `kore-tech-solutions.html` in any text editor.

| To change...              | Look for...                                  |
|----------------------------|-----------------------------------------------|
| Contact details            | `contact.koretechsolutions@gmail.com`, `wa.me/919168477851` |
| Colors                     | CSS variables at the top: `:root { --blue, --amber, ... }` |
| Founder bio/photo          | `<section class="founder" id="founder">`      |
| Projects                   | `.proj-grid` inside the Founder section       |
| Certifications             | `.cert-grid` inside the Founder section       |
| Services offered           | `<section class="services" id="services">`    |

---

## 📌 Notes

- The email "copy to clipboard" fallback requires the site to be served over **HTTPS** (or `localhost`) — GitHub Pages, Netlify, and Vercel all serve over HTTPS by default, so this works once deployed.
- All external links (projects, certificates, LinkedIn, GitHub) point to the live portfolio at `chandrakantkore.github.io/official_portfolio`.
- No backend, database, or server required — it's a static page.

---

Built with `</>` and a lot of coffee — Kore Tech Solutions, 2026.
