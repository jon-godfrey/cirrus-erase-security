# cirrus-erase-security

Public security policy + PGP keys for **Cirrus Erase**.

Live at https://security.cirruserase.com.

## What's here

- `index.html` — security contacts + disclosure policy
- `cirrus-erase-security.asc` — combined public PGP keys (primary + secondary contacts)
- `advisories/` — published security advisories (none yet)
- `CNAME` — `security.cirruserase.com`
- `.nojekyll` — GitHub Pages should serve plain HTML, not Jekyll-processed

## How to update

To rotate the secondary security contact:
1. Edit the relevant fields in `index.html`
2. Update `cirrus-erase-security.asc` with the new combined public key file
3. Commit + push to `main`
4. Site updates within ~1 min

No shim-review re-submission needed — the shim-review PR references this page URL, not the specific person.

## Report a vulnerability

See https://security.cirruserase.com or `index.html` in this repo.
