# Portfolio Bank

> One place to find, compare, and download the best open-source portfolio templates.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Stop scrolling through hundreds of random repos. **Portfolio Bank** is a curated collection of high-quality portfolio website templates — each with a live demo, GitHub link, tech stack, and clear download instructions.

---

## Quick start

**Want a portfolio today?** Pick a template below, then use one of these:

| Method | When to use | How |
|--------|-------------|-----|
| **Use as template** | Fastest — GitHub creates a repo for you | Click **Use this template** on the repo page |
| **Clone** | You want full git history | `git clone <repo-url>` |
| **Download ZIP** | No git needed | Repo → **Code** → **Download ZIP** |

Most templates need Node.js 18+. Typical setup:

```bash
git clone <repo-url>
cd <repo-name>
npm install    # or pnpm install / yarn
npm run dev    # open http://localhost:3000
```

Edit the config file (usually `config.js`, `portfolio.config.ts`, or `src/content/`) with your name, projects, and links. Deploy free on [Vercel](https://vercel.com), [Netlify](https://netlify.com), or [GitHub Pages](https://pages.github.com).

### Tags at a glance

Every template is labeled so you can scan quickly:

| Tag | Meaning |
|-----|---------|
| ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | Fully free & open source — no purchase needed |
| ![freemium](https://img.shields.io/badge/price-freemium-3b82f6?style=flat-square) | Free base version + optional paid upgrades |
| ![paid](https://img.shields.io/badge/price-paid-f97316?style=flat-square) | Requires a one-time purchase or subscription |

**Rating** is our editorial score out of 5 — based on design, docs, and how easy it is to set up.  
Example: `★★★★★` = 5/5 · `4.8/5` = precise score · `—` = not rated yet

---

## Contents

- [Featured picks](#featured-picks)
- [Next.js](#nextjs)
- [React](#react)
- [Vue.js](#vuejs)
- [Astro & modern static](#astro--modern-static)
- [Vanilla HTML / CSS / JS](#vanilla-html--css--js)
- [Academic & research](#academic--research)
- [Auto-generated from GitHub](#auto-generated-from-github)
- [Inspiration only](#inspiration-only)
- [How we pick templates](#how-we-pick-templates)
- [Contributing](#contributing)

---

## Featured picks

Hand-picked templates that balance design, maintainability, and ease of setup.

| Template | Price | Rating | Stars | Stack | Best for | Live demo | Get it |
|----------|:-----:|:------:|------:|-------|----------|-----------|--------|
| [Magic UI Portfolio](https://github.com/magicuidesign/portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ★★★★★ | ![stars](https://img.shields.io/github/stars/magicuidesign/portfolio?style=flat) | Next.js 14, Shadcn UI, Magic UI | Minimalist design, single config file, blog | [portfolio-magicui.vercel.app](https://portfolio-magicui.vercel.app) | [Repo](https://github.com/magicuidesign/portfolio) |
| [Sidefolio](https://github.com/manuarora700/sidefolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | 4.8/5 | ![stars](https://img.shields.io/github/stars/manuarora700/sidefolio?style=flat) | Next.js, Tailwind, Framer Motion, MDX | Sidebar layout, Aceternity UI animations | [Aceternity preview](https://ui.aceternity.com/template-preview/sidefolio-portfolio-template) | [Repo](https://github.com/manuarora700/sidefolio) |
| [Magic Portfolio](https://github.com/once-ui-system/magic-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ★★★★☆ | ![stars](https://img.shields.io/github/stars/once-ui-system/magic-portfolio?style=flat) | Next.js, MDX, TypeScript | Clean design, blog + projects | [magic-portfolio.com](https://magic-portfolio.com) | [Repo](https://github.com/once-ui-system/magic-portfolio) |
| [developerFolio](https://github.com/saadpasta/developerFolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ★★★★☆ | ![stars](https://img.shields.io/github/stars/saadpasta/developerFolio?style=flat) | React | Feature-rich, GitHub stats integration | [developerfolio.js.org](https://developerfolio.js.org) | [Repo](https://github.com/saadpasta/developerFolio) |
| [mldangelo personal-site](https://github.com/mldangelo/personal-site) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ★★★★★ | ![stars](https://img.shields.io/github/stars/mldangelo/personal-site?style=flat) | Next.js 16, Tailwind v4 | Minimal, fast, GitHub Pages deploy | [mldangelo.com](https://www.mldangelo.com) | [Repo](https://github.com/mldangelo/personal-site) |
| [masterPortfolio](https://github.com/ashutosh1919/masterPortfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ★★★★☆ | ![stars](https://img.shields.io/github/stars/ashutosh1919/masterPortfolio?style=flat) | React | Highly customizable, animated sections | [ashutoshhathidara.com](https://ashutoshhathidara.com) | [Repo](https://github.com/ashutosh1919/masterPortfolio) |
| [devportfolio](https://github.com/RyanFitzgerald/devportfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ★★★★☆ | ![stars](https://img.shields.io/github/stars/RyanFitzgerald/devportfolio?style=flat) | Astro, Tailwind | Minimal, professional, lightweight | [Demo](https://ryanfitzgerald.github.io/devportfolio) | [Repo](https://github.com/RyanFitzgerald/devportfolio) |
| [DevfolioX](https://github.com/KevinTrinhDev/DevfolioX) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ★★★★☆ | ![stars](https://img.shields.io/github/stars/KevinTrinhDev/DevfolioX?style=flat) | Next.js 16, React 19 | Config-driven JSON, PWA, integrations | [devfoliox.vercel.app](https://devfoliox.vercel.app) | [Repo](https://github.com/KevinTrinhDev/DevfolioX) |

---

## Next.js

Modern App Router templates with great SEO and performance.

| Template | Price | Rating | Stars | Highlights | Live demo | Repo |
|----------|:-----:|:------:|------:|------------|-----------|------|
| [Magic UI Portfolio](https://github.com/magicuidesign/portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ★★★★★ | ![stars](https://img.shields.io/github/stars/magicuidesign/portfolio?style=flat) | Shadcn UI + Magic UI, config file, blog | [portfolio-magicui.vercel.app](https://portfolio-magicui.vercel.app) | [Link](https://github.com/magicuidesign/portfolio) |
| [Sidefolio](https://github.com/manuarora700/sidefolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | 4.8/5 | ![stars](https://img.shields.io/github/stars/manuarora700/sidefolio?style=flat) | Aceternity UI, sidebar layout, MDX blog | [Aceternity preview](https://ui.aceternity.com/template-preview/sidefolio-portfolio-template) | [Link](https://github.com/manuarora700/sidefolio) |
| [said7388/developer-portfolio](https://github.com/said7388/developer-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | — | ![stars](https://img.shields.io/github/stars/said7388/developer-portfolio?style=flat) | Tailwind, blog, clean sections | [said7388.github.io](https://said7388.github.io/developer-portfolio) | [Link](https://github.com/said7388/developer-portfolio) |
| [1hanzla100/developer-portfolio](https://github.com/1hanzla100/developer-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | — | ![stars](https://img.shields.io/github/stars/1hanzla100/developer-portfolio?style=flat) | Config-driven, Bootstrap + Lottie animations | [hanzla.pro](https://hanzla.pro) | [Link](https://github.com/1hanzla100/developer-portfolio) |
| [Flexy Dev](https://github.com/AbdulBasit313/nextjs-portfolio-template) | ![freemium](https://img.shields.io/badge/price-freemium-3b82f6?style=flat-square) | — | ![stars](https://img.shields.io/github/stars/AbdulBasit313/nextjs-portfolio-template?style=flat) | SEO-focused, Formspree contact, services section | [nextjs-dev-portfolio.netlify.app](https://nextjs-dev-portfolio.netlify.app/) | [Link](https://github.com/AbdulBasit313/nextjs-portfolio-template) |
| [nextjs-tailwindcss-portfolio](https://github.com/realstoman/nextjs-tailwindcss-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | — | ![stars](https://img.shields.io/github/stars/realstoman/nextjs-tailwindcss-portfolio?style=flat) | Dark mode, Framer Motion, project filters | [Demo](https://realstoman.github.io/nextjs-tailwindcss-portfolio) | [Link](https://github.com/realstoman/nextjs-tailwindcss-portfolio) |
| [foliokit](https://github.com/akshay-bharadva/foliokit) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | — | ![stars](https://img.shields.io/github/stars/akshay-bharadva/foliokit?style=flat) | One config file, 30 themes, optional CMS | [Demo](https://akshay-bharadva.github.io/foliokit/) | [Link](https://github.com/akshay-bharadva/foliokit) |
| [Aiyu](https://github.com/aiyu-ayaan/Aiyu) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | — | ![stars](https://img.shields.io/github/stars/aiyu-ayaan/Aiyu?style=flat) | Full admin panel + CMS, PostgreSQL | [me.aiyu.co.in](http://me.aiyu.co.in) | [Link](https://github.com/aiyu-ayaan/Aiyu) |
| [Nim](https://github.com/ibelick/nim) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | — | ![stars](https://img.shields.io/github/stars/ibelick/nim?style=flat) | Ultra-minimal, fast | [nim-fawn.vercel.app](https://nim-fawn.vercel.app) | [Link](https://github.com/ibelick/nim) |

---

## React

Classic React portfolios — great if you're already in the React ecosystem.

| Template | Price | Stars | Highlights | Live demo | Repo |
|----------|:-----:|------:|------------|-----------|------|
| [developerFolio](https://github.com/saadpasta/developerFolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/saadpasta/developerFolio?style=flat) | Skills, blogs, GitHub integration | [developerfolio.js.org](https://developerfolio.js.org) | [Link](https://github.com/saadpasta/developerFolio) |
| [masterPortfolio](https://github.com/ashutosh1919/masterPortfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/ashutosh1919/masterPortfolio?style=flat) | Fully customizable sections | [ashutoshhathidara.com](https://ashutoshhathidara.com) | [Link](https://github.com/ashutosh1919/masterPortfolio) |
| [Dopefolio](https://github.com/rammcodes/Dopefolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/rammcodes/Dopefolio?style=flat) | Modern design, easy to tweak | [rammaheshwari.com](https://rammaheshwari.com) | [Link](https://github.com/rammcodes/Dopefolio) |
| [react-portfolio-template](https://github.com/chetanverma16/react-portfolio-template) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/chetanverma16/react-portfolio-template?style=flat) | Modern React starter | [react-portfolio-template.netlify.app](https://react-portfolio-template.netlify.app) | [Link](https://github.com/chetanverma16/react-portfolio-template) |
| [react-resume-template](https://github.com/tbakerx/react-resume-template) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/tbakerx/react-resume-template?style=flat) | Resume-style layout | [Demo](https://tbakerx.github.io/react-resume-template/) | [Link](https://github.com/tbakerx/react-resume-template) |
| [adrianhajdin portfolio](https://github.com/adrianhajdin/portfolio_website) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/adrianhajdin/portfolio_website?style=flat) | 3D elements, Framer Motion | [jsmastery.pro](https://www.jsmastery.pro) | [Link](https://github.com/adrianhajdin/portfolio_website) |
| [react-tailwindcss-portfolio](https://github.com/realstoman/react-tailwindcss-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/realstoman/react-tailwindcss-portfolio?style=flat) | Dark mode, project filters, animations | [react-tailwindcss-portfolio.netlify.app](https://react-tailwindcss-portfolio.netlify.app/) | [Link](https://github.com/realstoman/react-tailwindcss-portfolio) |

---

## Vue.js

| Template | Price | Stars | Highlights | Live demo | Repo |
|----------|:-----:|------:|------------|-----------|------|
| [vuejs-tailwindcss-portfolio](https://github.com/realstoman/vuejs-tailwindcss-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/realstoman/vuejs-tailwindcss-portfolio?style=flat) | Dark mode, multipage, project filters | [vuejs-tailwindcss-portfolio.netlify.app](https://vuejs-tailwindcss-portfolio.netlify.app/) | [Link](https://github.com/realstoman/vuejs-tailwindcss-portfolio) |
| [nuxtjs-tailwindcss-portfolio](https://github.com/realstoman/nuxtjs-tailwindcss-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/realstoman/nuxtjs-tailwindcss-portfolio?style=flat) | Nuxt.js version of the realstoman theme | [nuxtjs-tailwindcss-portfolio.netlify.app](https://nuxtjs-tailwindcss-portfolio.netlify.app/) | [Link](https://github.com/realstoman/nuxtjs-tailwindcss-portfolio) |

---

## Astro & modern static

Lightweight, fast, and great for static hosting.

| Template | Price | Stars | Highlights | Live demo | Repo |
|----------|:-----:|------:|------------|-----------|------|
| [devportfolio](https://github.com/RyanFitzgerald/devportfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/RyanFitzgerald/devportfolio?style=flat) | Astro + Tailwind, minimal | [Demo](https://ryanfitzgerald.github.io/devportfolio) | [Link](https://github.com/RyanFitzgerald/devportfolio) |
| [Magic Portfolio](https://github.com/once-ui-system/magic-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/once-ui-system/magic-portfolio?style=flat) | MDX content, gallery, CV page | [magic-portfolio.com](https://magic-portfolio.com) | [Link](https://github.com/once-ui-system/magic-portfolio) |
| [mldangelo personal-site](https://github.com/mldangelo/personal-site) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/mldangelo/personal-site?style=flat) | Next.js static export, GitHub Pages | [mldangelo.com](https://www.mldangelo.com) | [Link](https://github.com/mldangelo/personal-site) |

---

## Vanilla HTML / CSS / JS

No build step required — perfect for beginners or GitHub Pages.

| Template | Price | Stars | Highlights | Live demo | Repo |
|----------|:-----:|------:|------------|-----------|------|
| [vcard-personal-portfolio](https://github.com/codewithsadee/vcard-personal-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/codewithsadee/vcard-personal-portfolio?style=flat) | Beautiful vCard-style design | [codewithsadee.github.io](https://codewithsadee.github.io/vcard-personal-portfolio) | [Link](https://github.com/codewithsadee/vcard-personal-portfolio) |
| [responsive-portfolio-website-Alexa](https://github.com/bedimcode/responsive-portfolio-website-Alexa) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/bedimcode/responsive-portfolio-website-Alexa?style=flat) | Responsive, tutorial-friendly | [Demo](https://bedimcode.github.io/responsive-portfolio-website-Alexa) | [Link](https://github.com/bedimcode/responsive-portfolio-website-Alexa) |
| [developer-portfolio](https://github.com/yashrajnayak/developer-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/yashrajnayak/developer-portfolio?style=flat) | JSON config, GitHub Pages auto-setup | [yashrajnayak.github.io](https://yashrajnayak.github.io) | [Link](https://github.com/yashrajnayak/developer-portfolio) |
| [stomanstrap](https://github.com/realstoman/stomanstrap) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/realstoman/stomanstrap?style=flat) | Bootstrap 5, no React required | [stomanstrap.netlify.com](https://stomanstrap.netlify.com) | [Link](https://github.com/realstoman/stomanstrap) |

---

## Academic & research

For researchers, PhD students, and academics who need publications and CVs.

| Template | Price | Stars | Highlights | Live demo | Repo |
|----------|:-----:|------:|------------|-----------|------|
| [al-folio](https://github.com/alshedivat/al-folio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/alshedivat/al-folio?style=flat) | Publications, blog, Jekyll | [alshedivat.github.io/al-folio](https://alshedivat.github.io/al-folio) | [Link](https://github.com/alshedivat/al-folio) |
| [academicpages](https://github.com/academicpages/academicpages.github.io) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/academicpages/academicpages.github.io?style=flat) | Markdown-based academic site | [academicpages.github.io](https://academicpages.github.io) | [Link](https://github.com/academicpages/academicpages.github.io) |
| [HugoBlox](https://github.com/HugoBlox/hugo-blox-builder) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/HugoBlox/hugo-blox-builder?style=flat) | Hugo-based, research-focused | [hugoblox.com](https://hugoblox.com) | [Link](https://github.com/HugoBlox/hugo-blox-builder) |

---

## Auto-generated from GitHub

These build your portfolio from your GitHub profile — almost zero config.

| Template | Price | Stars | Highlights | Live demo | Repo |
|----------|:-----:|------:|------------|-----------|------|
| [gitprofile](https://github.com/arifszn/gitprofile) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/arifszn/gitprofile?style=flat) | Dynamic portfolio from GitHub username | [arifszn.github.io/gitprofile](https://arifszn.github.io/gitprofile) | [Link](https://github.com/arifszn/gitprofile) |
| [developer-portfolio](https://github.com/yashrajnayak/developer-portfolio) | ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) | ![stars](https://img.shields.io/github/stars/yashrajnayak/developer-portfolio?style=flat) | Auto-pulls starred/featured repos | [yashrajnayak.github.io](https://yashrajnayak.github.io) | [Link](https://github.com/yashrajnayak/developer-portfolio) |

---

## Inspiration only

Not templates — curated galleries of real portfolios for design ideas.

| Resource | Stars | Description | Link |
|----------|------:|-------------|------|
| [portfolio-ideas](https://github.com/Evavic44/portfolio-ideas) | ![stars](https://img.shields.io/github/stars/Evavic44/portfolio-ideas?style=flat) | Real portfolio examples by developers & designers | [Repo](https://github.com/Evavic44/portfolio-ideas) |
| [awesome-github-pages-portfolios](https://github.com/guilyx/awesome-github-pages-portfolios) | ![stars](https://img.shields.io/github/stars/guilyx/awesome-github-pages-portfolios?style=flat) | GitHub Pages portfolio roundup | [Repo](https://github.com/guilyx/awesome-github-pages-portfolios) |

---

## How we pick templates

A template earns a spot in Portfolio Bank when it:

1. **Is open source** with a clear license (MIT, Apache, etc.)
2. **Has a working live demo** so you can preview before downloading
3. **Is maintained** — commits within the last ~12 months (exceptions noted)
4. **Is actually a template** — not just someone's personal site with no reuse docs
5. **Has setup instructions** in the README

We prefer templates that are config-driven (edit a JSON/TS file, not React internals) but include advanced options too.

---

## Contributing

Found a great template? **[Open a PR](CONTRIBUTING.md)** — add it to the right category table with demo link, repo link, and a one-line description.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guide.

---

## License

This curated list is released under the [MIT License](LICENSE). Individual templates have their own licenses — check each repo before use.

---

<p align="center">
  <strong>Star this repo</strong> if it helped you find your portfolio — it helps others discover it too.
</p>
