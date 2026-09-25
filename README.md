# Kickoff Legends — public site

The public pages for the Kickoff Legends iOS app (App Store listing links and
AdMob verification). The game's source lives in the private `football` repo.

| Page | URL (after GitHub Pages is on) |
|---|---|
| Marketing / home | https://afonsoquinaz.github.io/kickofflegendspublic/ |
| Support URL | https://afonsoquinaz.github.io/kickofflegendspublic/support.html |
| Privacy Policy URL | https://afonsoquinaz.github.io/kickofflegendspublic/privacy.html |
| app-ads.txt | https://afonsoquinaz.github.io/kickofflegendspublic/app-ads.txt |

## Turn the site on (once)
GitHub → this repo → **Settings → Pages** → Source: *Deploy from a branch*,
Branch: `main`, folder `/ (root)` → Save. The URLs above work a minute later.

## app-ads.txt (AdMob "app-ads.txt not verified")
AdMob only accepts `app-ads.txt` at the **root of a domain** — the domain of the
*Marketing URL* (or developer website) in your App Store listing. A project page
like `afonsoquinaz.github.io/kickofflegendspublic/` is a sub-folder, so for
verification use one of:

1. **GitHub user site (free):** create a public repo named exactly
   `afonsoquinaz.github.io`, put this `app-ads.txt` at its root, enable Pages, and
   set the App Store *Marketing URL* to `https://afonsoquinaz.github.io`
   (that root also serves DEADGRID — both apps share the same publisher line).
2. **A custom domain** (e.g. `kickofflegends.com`) pointed at this repo
   (Settings → Pages → Custom domain); then `https://kickofflegends.com/app-ads.txt`
   is at the root. Set that domain as the Marketing URL.

Then AdMob → Apps → Kickoff Legends → **app-ads.txt → Check for updates**.
