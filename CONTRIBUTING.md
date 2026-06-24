# Contributing to Portfolio Bank

Thanks for helping grow this collection! Portfolio Bank is a curated list — quality over quantity.

## What to add

- Open-source **portfolio templates** (not personal sites unless they're explicitly reusable)
- Templates with a **live demo** and **setup instructions**
- Prefer actively maintained repos (commit in the last 12 months)

## What not to add

- Paid-only templates with no free tier
- Repos with no demo or broken demo
- Personal portfolios that aren't designed as templates
- Duplicate entries (search the README first)

## How to add a template

1. Fork this repo
2. Add your entry to the **most relevant category** in `README.md`
3. Use this card format (inside the matching `<details>` section):

```markdown
> ### [Template Name](https://github.com/user/repo)
>
> ![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square) ![rating](https://img.shields.io/badge/rating-not%20rated-94a3b8?style=flat-square) ![stars](https://img.shields.io/github/stars/user/repo?style=flat-square)
>
> One-line highlight
>
> 🔗 [Live demo](https://demo-url) · 📦 [Source code](https://github.com/user/repo)
```

**Price badges** — pick one:
- Free: `![free](https://img.shields.io/badge/price-free-22c55e?style=flat-square)`
- Freemium: `![freemium](https://img.shields.io/badge/price-freemium-3b82f6?style=flat-square)`
- Paid: `![paid](https://img.shields.io/badge/price-paid-f97316?style=flat-square)`

**Rating** — always use a numeric badge (`X/5`), never star characters. Examples:
- `![rating](https://img.shields.io/badge/rating-4.5%2F5-22c55e?style=flat-square&logo=star&logoColor=white)`
- Not reviewed yet: `![rating](https://img.shields.io/badge/rating-not%20rated-94a3b8?style=flat-square)`

4. Open a pull request with:
   - Template name and why it's worth including
   - Confirmation that the demo works
   - License type (MIT, Apache, etc.)

## Pull request checklist

- [ ] Live demo link works
- [ ] GitHub repo is public and open source
- [ ] Entry is in the correct category
- [ ] Price tag is correct (free / freemium / paid)
- [ ] Rating badge uses `X/5` format (or `not rated` if not reviewed)
- [ ] No duplicate of an existing entry

## Suggesting removals

If a template is abandoned, demo is dead, or repo was removed, open an issue or PR to remove it. Note the reason in the PR description.
