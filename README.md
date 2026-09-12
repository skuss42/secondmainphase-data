# secondmainphase-data

Nightly set-valuation data for secondmainphasetrading.com, written by the
price pipeline on the AI-Agent droplet and read by the site build. Published
content only - the same numbers appear on the public site.

- `set-values.json` - per-set market value, movers, top cards. Refreshed daily ~11:05 UTC.

The code repository never receives a push from the droplet; a scheduled
GitHub Action in it fetches this file and commits it there.
