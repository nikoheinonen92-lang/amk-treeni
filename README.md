# AMK-valintakoeharjoittelu

Selaimessa toimivat harjoitteluohjelmat ammattikorkeakoulujen valintakokeeseen.

| Kansio | Sisältö |
|---|---|
| `index.html` | Etusivu, josta pääsee molempiin sovelluksiin |
| `matematiikkatreeni/` | AMK-matematiikkatreeni: oppimispolku, tehtävägeneraattori, vihjeet, koesetit |
| `valintakoetreeni/` | AMK-valintakoetreeni: kaikki koeosiot, viikko-ohjelma, koetila |
| `data/` | Tehtäväpankit JSON-muodossa (valinnainen, tuodaan sovelluksen Tiedot-välilehdeltä) |
| `.nojekyll` | Kertoo GitHub Pagesille, että tiedostot julkaistaan sellaisenaan |

## Julkaisu GitHub Pagesiin

1. Kirjaudu osoitteessa github.com ja valitse **New repository**.
   - Nimi esimerkiksi `amk-treeni`.
   - Näkyvyys **Public**. Ilmaisella GitHub-tilillä Pages toimii vain julkisessa repositoriossa.
   - Valitse **Create repository**.
2. Valitse tyhjän repositorion sivulta **uploading an existing file**.
3. Pura zip-paketti koneellesi. Vedä **kansion sisältö** (index.html, README.md ja kansiot matematiikkatreeni, valintakoetreeni ja data) latausalueelle. Älä vedä itse zip-tiedostoa.
4. Valitse **Commit changes**.
5. Avaa **Settings → Pages**. Valitse kohdassa Build and deployment:
   - Source: **Deploy from a branch**
   - Branch: **main** ja kansio **/ (root)**
   - Valitse **Save**.
6. Odota 1–3 minuuttia ja päivitä sivu. Osoite näkyy Pages-sivun yläreunassa:
   - Etusivu: `https://KÄYTTÄJÄNIMI.github.io/amk-treeni/`
   - Matematiikkatreeni: `https://KÄYTTÄJÄNIMI.github.io/amk-treeni/matematiikkatreeni/`

Jaa näistä se linkki, jonka haluat. Linkki toimii WhatsAppissa ja sähköpostissa, ja se avautuu iPhonella Safarissa.

## Päivittäminen

Avaa repositoriossa kansio, valitse **Add file → Upload files** ja lataa uusi `index.html` vanhan päälle. Julkaistu sivu päivittyy minuutin parin kuluessa. Käyttäjien tallentamat tulokset säilyvät, kun osoite pysyy samana.

## Huomioitavaa

- Tulokset tallentuvat vain käyttäjän omaan selaimeen. Kukaan muu, ei myöskään repositorion omistaja, näe niitä.
- Julkisen repositorion tiedostot ja sivu ovat kaikkien nähtävissä.
- Harjoitustehtävät ovat omia harjoitustehtäviä, eivät virallisia koetehtäviä.
