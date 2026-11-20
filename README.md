# TezBooks — tezbooks.com

* `/` — the TezBooks website (Elite Kaiiser).
* `/app/` — the shop owner's phone dashboard: today's sales, cash and dues. Opened from
  TezBooks → Settings → Owner's phone dashboard (the link carries the shop's private view key).
  The data is encrypted per shop; this page holds no shop data.

Hosting: Cloudflare Pages (project "tezbooks", account 33quintillion). Every push to `main` is
published to tezbooks.com by Cloudflare — no build step, no GitHub Pages or Actions. Files must stay
under 25 MB each. www.tezbooks.com redirects to tezbooks.com (Cloudflare redirect rule).

© Elite Kaiiser.
