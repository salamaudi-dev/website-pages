# Growisto — Landing Pages

## Repo

- GitHub: https://github.com/salamaudi-dev/website-pages
- Branch: `gh-pages` (this is what GitHub Pages serves)
- Local path: `/Users/salamayusuf/Desktop/Claude code/landing-pages/`

## Live Pages

| Page | File | URL |
|---|---|---|
| Amazon SEO | `amazon-seo.html` | https://salamaudi-dev.github.io/website-pages/amazon-seo.html |
| Shopify Plus Development | `shopify-plus-development.html` | https://salamaudi-dev.github.io/website-pages/shopify-plus-development.html |

## To deploy a new page

```bash
git add <filename>.html
git commit -m "Add <service> landing page"
git push origin gh-pages
```

Live URL pattern: `https://salamaudi-dev.github.io/website-pages/<filename>.html`

The repo is public. GitHub Pages is configured on the `gh-pages` branch.

---

## Brand System

```css
--navy:    #0F1F3D;   /* nav, dark sections, headings */
--teal:    #2B7A8B;   /* primary accent, active tabs */
--teal-lt: #E6F4F6;   /* solution callout backgrounds */
--mint:    #EBF5F4;   /* light section backgrounds */
--orange:  #E35D34;   /* CTA buttons */
--orange-h:#C94D28;   /* button hover */
--dark:    #1A1A2E;   /* AI toolset background, final CTA */
--text:    #3D3D4E;   /* body copy */
--grey:    #6B7280;   /* secondary text */
--grey-lt: #E8EAED;   /* borders */
--white:   #FFFFFF;
--card-bg: #F9FAFB;
--gold:    #F5B731;   /* star ratings */
--purple:  #6C4BA6;   /* accent use */
font-family: 'Poppins', sans-serif;
```

---

## H-Tag Rules (enforce on every page)

- **One H1** per page — hero headline only
- **H2** — section titles only (never nav, footer, or card labels)
- **H3** — sub-items within a section (reason cards, case study titles, FAQ questions, process steps)
- **p tags** — hero subtext, form card labels, footer column labels, stat labels, testimonial names
- Footer labels: always `<p class="footer-col-label">`, never `<h4>`

---

## Services

- **CRO / Website Development** — Live website audits across 9 levers and 600+ parameters
- **Amazon SEO** — Listing optimization, marketplace strategy
- **GEO / SEO** — AI-driven organic search
- **TikTok Shop** — TikTok commerce strategy
- **Walmart** — Walmart marketplace

---

## Key Links


- CRO Audit Sample: https://docs.google.com/presentation/d/1hKK1dsDdW3scrkgZUof84OG6JqZK-s3pRJT6Jt6pjLc/edit
- Case Study (11% CR improvement): https://docs.google.com/presentation/d/1xtWUdAWYE8pmd8c9qsWn4ebKQAu9DYb_Sx6lsaGOEZE/edit
- Growth Tribe booking link: https://cal.com/team/growisto/the-growth-tribe-x-growisto-cro-website-discovery-call
- Ecom Circle booking link: https://cal.com/team/growisto/ecom-circle-x-growisto-cro-website-discovery-call

---

## Reference Documents

| Document | Link | When to use |
|---|---|---|
| Brand Guidelines | https://drive.google.com/file/d/1qarWQT1xNTPNICOZGXjnqm3KQedAxb0t/view?usp=sharing | Before building any page — check colors, typography, logo usage, tone |
| Master Service Deck (Ecommerce US 2026) | https://docs.google.com/presentation/d/1GFu2bsOemC1xJOzK0es0I0oJmpFKVH2cGo6PBz5vHo4/edit | Verify all service descriptions, positioning, and claims against this |
| GrowistoAI Wiki | MCP connector — use the GrowistoAI Wiki tool | Any time you need to look up company information, services, or internal data |

---

## Required Inputs Before Starting Any Page

Always ask the user for these before building:

1. **Content doc** — Google Doc URL with all copy for the page (headlines, pain points, services, case studies, FAQs, etc.)
2. **Reference live page** — URL of an existing page to use as design reference
3. **Service name and filename** — e.g. `cro.html`, `geo-seo.html`
