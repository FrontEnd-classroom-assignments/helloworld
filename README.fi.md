# Hei maailma

### 1. Luo komponentti
Luot yksinkertaisen React-komponentin, joka näyttää tervehdysviestin. Tämä tehtävä auttaa sinua harjoittelemaan komponenttien luomista, JSX:n käyttöä ja propsejen välittämistä.

Luo React-projektiisi uusi tiedosto nimeltä `Greeting.tsx`. Määritä tähän tiedostoon uusi React-komponentti nimeltä `Greeting`.

Tämän komponentin tulee palauttaa seuraava HTML:
```
<h3>Hei maailma!</h3>
```
### 2. Käytä Greeting-komponenttia App.tsx:ssä
Avaa App.tsx-tiedosto ja tuo `Greeting`-komponentti.

Käytä `Greeting`-komponenttia `App`-komponentin `return`-lauseessa, jotta Hei maailma! -viesti näkyy verkkosivulla.

### 3. Käytä propseja

Välitä propsit `Greeting`-komponentille ja päivitä `Greeting`-komponentti ottamaan vastaan prop


Näytä propin sijaan teksti "Hei {name}!" sen sijaan, että näytetään "Hei maailma!".

Esimerkiksi, jos välität nimeksi Alex, komponentti näyttää Hei Alex!.

> [!IMPORTANT]
> Kaikki Github Classroom -tehtävät tällä kurssilla sisältävät GitHub-workflown, joka tarkistaa koodisi automaattisesti linterin avulla. Täyden pistemäärän saadaksesi workflow’n tulee mennä läpi ilman virheitä.
> Ennen kuin palautat tehtävän, voit ajaa linterin paikallisesti tietokoneellasi seuraavalla komennolla:
> ```
> npm run lint
> ```
