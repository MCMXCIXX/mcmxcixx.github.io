# mcmxcixx.github.io — Northlight Studio (root site)

This is the **root GitHub Pages site** for the user `MCMXCIXX` → served at **https://mcmxcixx.github.io/**.
It's a one-page studio "visit card" that links to the templates, and it doubles as the page that **claims the `mcmxcixx.github.io` domain on Pinterest** (which then covers every project demo under it, e.g. `/lumen-saas-landing/`).

## Publish (one time)
1. On GitHub, create a **new repository named exactly `mcmxcixx.github.io`** (must match your username).
2. Push this folder's contents to it (`main` branch).
3. **Settings → Pages → Deploy from branch → `main` / root.** In ~1 min it's live at `https://mcmxcixx.github.io/`.

## Claim the domain on Pinterest
1. Pinterest (Business account) → **Settings → Claimed accounts → Claim → Website** → enter `mcmxcixx.github.io` → **Add HTML tag**.
2. Copy the value Pinterest gives you into `index.html` here — replace `PASTE_YOUR_PINTEREST_CODE_HERE` in:
   ```html
   <meta name="p:domain_verify" content="PASTE_YOUR_PINTEREST_CODE_HERE" />
   ```
3. Commit + push, wait for `https://mcmxcixx.github.io/` to update, then click **Verify** in Pinterest.
4. Done — the whole domain (incl. all `/template/` demo subpaths) is claimed → unlocks Rich Pins, analytics, and posting via Publer.

## Files
- `index.html` — the studio page (self-contained, inline CSS, no build step).
- `lumen.jpg` — preview thumbnail for the Lumen card.
- `.nojekyll` — serve assets without Jekyll processing.

To add a template to the collection, duplicate the Lumen `<article class="card">` block in `index.html`.
