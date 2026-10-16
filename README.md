# NML Consulting Group — nml consulting group llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `nmlconsultinggroupllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/nmlconsultinggroupllc.mjs`).
> To change the content, edit that file and run `node build.mjs nmlconsultinggroupllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@nmlconsultinggroupllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Per provider / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
NML Consulting Group LLC, a Florida limited liability company (document number L21000392722), advises independent medical and dental practices: reviewing operations and patient flow to find where schedule time and staff effort are actually going, managing provider credentialing and payer enrolment so clinicians can be paid, supporting the written compliance programme a practice is expected to maintain, and guiding practice start-up from entity and licensure through to opening. Engagements are scoped and quoted in writing. The company is not a law firm, a billing company or a staffing agency. Site: nmlconsultinggroupllc.shop
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
