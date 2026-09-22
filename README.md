# Vitablendz

Ny frontend for Vitablendz, frozen yogurt- og juicebar på Arkaden Torgterrassen i Stavanger.

Statisk HTML/CSS/JS, klart for Netlify. Ingen byggesteg.

## Fargepalett (fra logo.jpg)

Samplet fra merkevaren — **ikke beige, ikke gull**:

| Rolle | Hex | Kilde i logo |
| --- | --- | --- |
| Bladgrønn | `#1F7A30` / `#287C38` | «Vitablendz»-teksten og bladet |
| Dyp grønn | `#0E3B18` | Bunntekst / kontrast |
| Eplerød | `#B40A0A` / `#C81010` | Eplet og «Blend your Boost» |
| Ismynte / hvit | `#F4FBF5` / `#E8F6EB` | Kjølig bakgrunn |

Typografi: Fraunces (overskrifter) + Manrope (brødtekst).

## Sider

- `index.html` — hero, utvalgte produkter, om oss, kart
- `meny.html` — Frozen yogurt, Smoothieshakes, Superjuice, Iskaffe, Green tea latte
- `om-oss.html` — sted, løftet om iskaffe/matcha, arbeidsmåte
- `kontakt.html` — info, Netlify-skjema, kart, Facebook og Instagram

## Kontakt brukt i redesignet

Fra originalkoden, med én retting:

- Adresse: **Klubbgata 5, Arkaden Torgterrassen, 4013 Stavanger**
- E-post: **info@vitablendz.no**
- Åpent: hverdager **10:00–20:00**, lørdag **10:00–18:00** (søndag ikke oppgitt → stengt)
- Telefon: originalen hadde placeholder `(+47) 00000000`. Erstattet med det offentlig listede nummeret **958 24 330**. Bytt tilbake i HTML om det er feil.
- Sosiale medier: [Facebook](https://www.facebook.com/Vitablendzstavanger/) og [Instagram](https://www.instagram.com/vitablendz/)

## Tekstretter

- «Fruktsmoothie og rist jeg en drikk» → «Fruktsmoothie og shake i én drikk»
- Meny ligger på egne sider i stedet for Bootstrap-modaler
- Logo brukes med beskrivende alt-tekst, ikke tom `alt=""`

Prisene er uendret: **fra 40 kr** i alle kategorier.

## Bytt bilder

Filene ligger i `assets/images/` med rene navn. Overstyr med egne foto uten å røre CSS.

## Publiser

Last opp mappen `vitablendz` til Netlify (publish directory = rot med `index.html`). Kontaktskjemaet bruker Netlify Forms (`name="kontakt"`).
