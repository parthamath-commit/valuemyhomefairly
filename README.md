# Value My Home Fairly

Landing site for valuemyhomefairly.com (Pal Initiatives LLC).

- `site/index.html` — national homepage + "notify me" form (Netlify form `expansion`)
- `site/cincinnati/index.html` — Hamilton County launch page + waitlist form (Netlify form `waitlist`)
- `site/thanks.html` — confirmation page after either form

Hosting: Netlify, auto-deploys from the `main` branch (publish folder `site/`, set in `netlify.toml`).
Forms: Netlify Forms with honeypot field `bot-field`. Don't rename it to anything autofill might fill (e.g. "company").
DNS: Cloudflare, CNAME `@` and `www` → Netlify, proxy OFF (grey cloud).

Repository is public (needed for Netlify free-plan deploys). It holds only public website files: no keys, passwords or signup data.
