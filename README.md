# B FIT — Budimir Krivokuća

Statična sajt stranica (HTML + slike, bez build koraka).

## Hostovanje na GitHub Pages

1. Napravi novi repozitorijum na GitHubu.
2. Ubaci sve fajlove iz ovog projekta u koren repozitorijuma (index.html, support.js, image-slot.js i sve .png fajlove).
3. Settings -> Pages -> Source: "Deploy from a branch", grana main, folder / (root).
4. Sačuvaj. Sajt će biti dostupan na https://<korisnik>.github.io/<repo>/

Fajl .nojekyll je uključen da GitHub ne preskače fajlove.

## Fajlovi

- index.html - stranica (ista sadržina kao "B FIT.dc.html")
- support.js, image-slot.js - runtime skripte, moraju stajati pored index.html
- hero-budimir.png, portret-budimir.png, cilj-0*.png, usluga-0*.png, prica-0*.png, rezultat-0*.png, avatar-0*.png, cta-pozadina.png - fotografije

## Izmene

Uređuj "B FIT.dc.html", pa ponovo kopiraj njegovu sadržinu u index.html pre deploya.
