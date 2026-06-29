# YHDESSÄ – toimintamallin landing page

Yhden tiedoston staattinen verkkosivu (`index.html`) Saran "YHDESSÄ"-toimintamallille.
Toimii suoraan selaimessa ja mobiilissa, ei vaadi ylläpitoa.

## Rakenne

- `index.html` – koko sivu (HTML, CSS ja JS samassa tiedostossa)
- `kuvia/` – verkkoa varten pakatut valokuvat (PowerPointin kuvapankista)
- `Vuosikellon suunnittelua.pdf` – Saran alkuperäinen brief / spesifikaatio

## Avaaminen

Tuplaklikkaa `index.html` – aukeaa selaimeen. Ei asennuksia.

## Materiaalipankin linkit (TÄRKEÄÄ)

Materiaalipankin painikkeet ovat tällä hetkellä **placeholdereita** (merkitty "Tulossa").
Kun materiaali on valmis, etsi `index.html`:stä kyseinen rivi, esim.:

```html
<a class="mat-item" href="#" target="_blank" rel="noopener">...Aloitusviesti huoltajille...</a>
```

1. Vaihda `href="#"` materiaalin osoitteeksi, esim. `href="https://docs.google.com/..."`
2. Poista samalta riviltä `<span class="tulossa">Tulossa</span>`

## Julkaisu (ilmainen)

Sivun voi julkaista esim. **GitHub Pages**- tai **Netlify**-palvelussa ilmaiseksi.
Pyydä apua julkaisuun, kun sisältö on valmis.

## Huom

- Värit ja kuvat noudattavat Saran briefiä (raikas, sensitiivinen).
- Kaikki sisältö on muokattavissa – tämä on luonnos yhdessä hiottavaksi.
