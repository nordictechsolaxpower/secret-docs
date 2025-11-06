# Hemlig GitHub Pages-portal (noindex)

Detta repo är avsett för interna guider som inte ska indexeras av sökmotorer.
Allt innehåll nås endast via exakt URL (ingen inloggning).

## Så här använder du
1. Ladda upp mappen till ett nytt GitHub‑repo.
2. Aktivera **Settings → Pages** → Deploy from branch (main / root).
3. (Valfritt) Lägg din sida under en svår path, ex: `https://user.github.io/repo/a19h2d4/`.
4. Lägg fler HTML/PDF under `public/` och länka dem från `index.html`.

## Anti‑indexering
- `robots.txt` med `Disallow: /`
- `<meta name="robots" content="noindex, nofollow">` i alla HTML‑filer
- (Valfritt) Sätt `X‑Robots‑Tag: noindex, nofollow` via Cloudflare header‑regel.
