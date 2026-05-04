# Niittyharju Consulting — verkkosivuston lähdetiedostot

Tämä on staattinen kopio sivustosta `niittyharju.fi` (Webflow-vienti), joka on tarkoitettu hostattavaksi GitHub Pagesilla.

## Sisältö

- `index.html` — pääsivu
- `css/` — tyylit (normalize.css, components.css, niittyharjuconsulting.css)
- `js/` — sivuston JavaScript
- `images/` — kaikki kuvat (responsiiviset versiot eri kokoisille näytöille)
- `fonts/` — paikalliset fontit (Font Awesome ja Sovana)
- `robots.txt`

## Julkaisu GitHub Pagesissa

1. Luo uusi repo GitHubissa, esim. `niittyharju-site` (tai `<käyttäjänimi>.github.io` jos haluat sivuston juuriosoitteeseen).
2. Lataa kaikki tämän kansion tiedostot repon juureen.
3. Mene repon **Settings → Pages**, valitse lähteeksi `Deploy from a branch`, branch `main` ja kansio `/ (root)`.
4. Liitä oma domain `niittyharju.fi` Custom domain -kenttään ja päivitä DNS-tietueet osoittamaan GitHub Pagesin IP-osoitteisiin.

## DNS-asetukset (jos haluat oman domainin)

Lisää domainin hallintapaneeliin (esim. Xetnet) seuraavat A-tietueet juuridomainille:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Ja CNAME-tietue `www`-aliasalalle:

```
www  ->  <käyttäjänimi>.github.io
```
