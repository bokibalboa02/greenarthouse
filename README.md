# Green Art House — sajt

Statičan sajt, spreman za GitHub Pages. Nema build koraka, nema zavisnosti.

## Sadržaj

- `index.html` — glavna strana
- `pravilnik.html` — Pravilnik kuće
- `uploads/` — fotografije galerije (obavezno prebaciti zajedno sa HTML fajlovima)
- `.nojekyll` — govori GitHub Pages-u da ne procesira fajlove

## Postavljanje na GitHub Pages

1. Napravi novi repozitorijum na GitHub-u (npr. `green-art-house`).
2. Prebaci sadržaj ovog foldera u koren repozitorijuma i pošalji na `main` granu.
3. U repozitorijumu: **Settings → Pages**.
4. Pod *Build and deployment → Source* izaberi **Deploy from a branch**.
5. Grana: `main`, folder: `/ (root)`. Sačuvaj.
6. Za minut-dva sajt je na `https://<korisnik>.github.io/<repo>/`.

## Sopstveni domen

U **Settings → Pages → Custom domain** upiši domen (npr. `greenarthouse.rs`), pa kod registrara dodaj:

- `A` zapise ka `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- ili `CNAME` ka `<korisnik>.github.io` za `www` poddomen

Zatim uključi **Enforce HTTPS**.

## Kontakt forma

Dugme „Pošalji poruku" otvara mejl program gosta sa unetim podacima. Ako želiš da poruke stižu direktno na mejl bez tog koraka, potreban je servis kao Formspree.
