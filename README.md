# jasinski.app

Static site for [jasinski.app](https://jasinski.app), hosted on GitHub Pages.

## Live paths

- `/` — temporary landing
- `/neta/privacy/` — Neta privacy policy (PL / EN / UK)

## DNS (Squarespace Domains / Google Domains)

Point the apex domain to GitHub Pages with these **A** records (remove the old Squarespace A record):

| Type | Host | Value |
|------|------|-------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `kamiljasinski191.github.io` |

After DNS propagates, GitHub Pages will issue HTTPS for `jasinski.app`.
