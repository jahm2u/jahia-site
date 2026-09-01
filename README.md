# jahias.com — JAH IA Tecnologias

Corporate site for **JAH IA TECNOLOGIAS LTDA** (CNPJ 68.591.678/0001-20),
the Brazilian entity behind the Duda app.

Static HTML, no build step. Deployed to GitHub Pages from `main` by
`.github/workflows/pages.yml`.

## Why this site exists

Apple cancelled Developer Program enrolment `585U3H286G` because the
organization's website did not meet their guideline: it must be active, public,
and carry **a domain name associated with the organization**. `ajudaduda.com`
is the product site — its WHOIS names no organization and it never identified
the legal entity. This site does both.

Keep the legal identification block in `index.html` byte-identical to the
Receita Federal record. Apple cross-checks it against the D-U-N-S entry.

## Editing

Edit `index.html`, push to `main`, Pages redeploys. `CNAME` pins the custom
domain — do not delete it, Pages rewrites the domain setting on every deploy.
