# H Travels — Statična web stranica (hrvatski)

Stranica je pripremljena za objavu na GitHub Pages pod repozitorijem `Hrva-Mrva/Hrva-Mrva.github.io`.

## Što zamijeni/upečati prije objave
- U mapu `assets/` dodaj:
  - `logo.png` — tvoj optimizirani logo s prozirnom pozadinom (preporučeno 512x512 ili 256x256)
  - `favicon.png` — ikona (npr. 32x32)
  - `hero.jpg`, `destination1.jpg`, `destination2.jpg`, `destination3.jpg` — slike destinacija (možeš koristiti slobodne slike sa Unsplash)
- Ako želiš, umijeni `mailto:` email u kontakt formi s nekim servisom (Formspree / Netlify Forms) za pouzdanu isporuku.

## Kako brzo objaviti (web sučelje)
1. Na GitHubu napravi novi repozitorij s imenom: `Hrva-Mrva.github.io` (public).
2. Uploadaj sve fajlove i folder `assets/` u root repozitorija.
3. Za repozitorij `username.github.io` GitHub Pages automatski objavljuje iz glavne grane; stranica će biti dostupna na: `https://Hrva-Mrva.github.io/`.

## Kako objaviti pomoću Git (lokalno)
1. Na računalu u praznom folderu:
   - git init
   - git add .
   - git commit -m "Initial commit"
2. Na GitHubu stvori repozitorij `Hrva-Mrva.github.io` (public).
3. Poveži i pushaj:
   - git branch -M main
   - git remote add origin https://github.com/Hrva-Mrva/Hrva-Mrva.github.io.git
   - git push -u origin main
4. Otvori https://Hrva-Mrva.github.io/ (može potrajati minutu ili dvije).

## Kako ukloniti pozadinu loga (ako želiš bolji logo)
- Najbrže (online): https://www.remove.bg/ — uploadaj sliku, preuzmi PNG s prozirnom pozadinom.
- Besplatno u browseru: https://www.photopea.com/ — File > Open > Magic Cut / manualno odaberite i izbrišite pozadinu, pa File > Export as > PNG.
- Ako koristiš Photoshop: Select Subject → Select and Mask → Output to New Layer with Transparency → Export PNG.
- Nakon što imaš `logo.png` s prozirnom pozadinom, zamijeni `assets/logo.png` i `assets/favicon.png` (po potrebi).

## Potrebna pomoć
Ako želiš, mogu:
- pripremiti ZIP s gore navedenim datotekama za skidanje (poslat ću sadržaj ili upute kako napraviti),
- ili te voditi korak‑po‑korak dok napraviš repo i push‑aš (napiši kad si spreman i ja ću ti dati točne naredbe koje trebaš pokopirati).