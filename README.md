# ANTOM SEVEN LLC — Corporate Website

Static website (HTML/CSS/JS/SVG, no build step). Fonts self-hosted (Inter, Manrope — SIL OFL). No external requests.

## Data used (source)
| Field | Value | Source |
|---|---|---|
| Legal name | ANTOM SEVEN LLC | Articles of Organization (WY SOS, filed Nov 23, 2026, ID 2026-002142067) |
| Entity / State | Limited liability company / Wyoming | Articles of Organization |
| Principal office & mailing | 525 Randall Ave, Ste 100-890, Cheyenne, WY 82001 | Articles of Organization |
| Registered agent | Registered Agents Inc, 30 N Gould St, Ste R, Sheridan, WY 82801 | Articles of Organization |
| Activity | Marketing and creative services; content creation; communication solutions for brands and businesses | Client intake |
| E-mail | anmosqrey@gmail.com | Client intake |

## Not published (on purpose)
Owner/member name, passport data, phone number (+57, foreign — publish only if the client confirms), EIN (not issued yet), organizer data.

## Structure
```
index.html  about.html  privacy.html  terms.html
style.css   script.js   vercel.json   README.md
assets/  logo-mark.svg favicon.svg hero-creative.svg about-creative.svg
         apple-touch-icon.png og-image.png fonts/
```

## Domain
No domain provided yet. HTML files contain no domain (no canonical / og:url). When the domain is defined (e.g. DOMINIO.com), optionally add to each page `<head>`:
`<link rel="canonical" href="https://www.DOMINIO.com/">` and make `og:image` absolute.

## Deploy — GitHub + Vercel
1. Create a GitHub repository and upload all files in this folder (keep the structure).
2. Vercel → Add New → Project → import the repo.
   - Framework Preset: **Other**
   - Root Directory: `./`
   - Build Command / Output Directory / Install Command: **empty**
3. Deploy.
4. Settings → Domains: add `www.DOMINIO.com` (Production) and `DOMINIO.com` (redirect 308 → www).

## DNS (at the registrar)
| Type | Name | Value |
|---|---|---|
| A | `@` | `216.198.79.1` |
| CNAME | `www` | `cname.vercel-dns.com` |

Use the exact DNS values shown by Vercel if Vercel provides project-specific records.
Do not delete MX, SPF, DKIM, DMARC or Google verification records used for email.

## Notes for KYC
- Address 525 Randall Ave, Ste 100-890 is a virtual/mail-handling address. It must match the address used on bank/fintech applications.
- E-mail is @gmail.com. A domain e-mail (e.g. contact@DOMINIO.com) is recommended once the domain exists.
