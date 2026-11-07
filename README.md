# AB Zeb Willems — residential building & project development

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `abzebwillems.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/abzebwillems.mjs`).
> To change the content, edit that file and run `node build.mjs abzebwillems` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@abzebwillems.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
AB Zeb Willems is a company in Vorselaar in the province of Antwerp, building homes and developing building projects since October 2022. The largest sum a client on a rebuild can lose through inadvertence is not a cost overrun. It is fifteen points of VAT. Demolition followed by reconstruction of a dwelling can be invoiced at six per cent instead of twenty-one, and since January 2024 that national regime is permanent but conditional: the dwelling must be the client's sole and own dwelling, its habitable surface must not exceed two hundred square metres, the client must be domiciled there, and it must be kept for five years. From January 2025 the regime also covers reconstruction followed by long-term letting to a private individual as their main residence. The part that catches people is procedural rather than substantive: a declaration has to be lodged before the VAT becomes chargeable, and lodging it after work has been invoiced does not recover the rate. We therefore settle the position before the first invoice, not during the build, and we send clients to their own adviser for the answer itself. Site: abzebwillems.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
