# Milutin & Milica · sajt

Igraonica i čuvaonica za decu · TC Roda, drugi sprat, Save Kovačevića 48a, 34000 Kragujevac.
Adresa sajta: https://igraonicakragujevac.com/

## Stranice
- `index.html` – početna
- `igraonica.html`, `cuvaonica.html`
- `blog.html` + 3 blog teksta
- `mm-sub.css` – stilovi za podstranice
- `uploads/` – slike, logo i video
- `sitemap.xml`, `robots.txt`, `og-image.jpg`, `CNAME`, `.nojekyll`

## Objavljivanje na GitHub Pages sa domenom
1. Otpremite **ceo sadržaj** ovog foldera u koren repozitorijuma (uključujući skrivene fajlove `.nojekyll` i `CNAME`).
2. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save.
3. Settings → Pages → Custom domain: `igraonicakragujevac.com` → Save, pa uključite "Enforce HTTPS" kad postane dostupno.
4. Kod registra domena podesite DNS:
   - `A` zapisi za `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` zapis: `www` → `misicv89-ops.github.io`
5. U Google Search Console dodajte property za `https://igraonicakragujevac.com/` i pošaljite `sitemap.xml`.
