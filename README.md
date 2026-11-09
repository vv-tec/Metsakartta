# Metsakartta

Talokartan metsätilat: kiinteistöt, joilla on metsämaata yli 2 ha, puuston laskennallinen arvo, puusto, ikärakenne ja
metsäpohja avoimista aineistoista. Metsätilat näkyvät **Talokartassa** (metsätilanäkymä); tämä repositorio **ajaa
metsätilojen laskennan ja julkaisee karttatiedostot**, joita Talokartta lukee. Erillinen julkaisu on tarpeen, koska
talot (~0,5 Gt) ja metsätilat (~0,5 Gt) eivät mahdu yhden GitHub Pages -sivuston 1 Gt:n rajaan.

- Näkymä: https://vv-tec.github.io/Talokartta/?moodi=metsa (tämän repositorion etusivu ohjaa sinne)
- Karttatiedostot: https://vv-tec.github.io/Metsakartta/data/ (meta.json, f-*.pmtiles, kortit/, r.pmtiles)
- Koodi: [vv-tec/Talokartta](https://github.com/vv-tec/Talokartta) – laskenta `pipeline/metsa/`, näkymä `web/metsa.js`
- Kehittäjän muistio: Talokartan `CLAUDE.md` · omistajan ohje: Talokartan `KAYTTOOHJE.md`
- Ajo: Actions → **Päivitä metsätilat ja julkaise** (joka aamu noin klo 6.47 ja käsin). Ajo alkaa Talokartan
  pikatesteillä; julkaisun jälkeen metsätilanäkymä tarkistetaan selaimella (Talokartan `check/metsa_tarkistus.mjs`).
  Tarvitsee salaisuuden `MML_API_KEY`. Epäonnistunut ajo avaa ilmoituksen (issue), julkaistuna pysyy edellinen versio.

Lähteet: Suomen metsäkeskus (metsävaratieto), Maanmittauslaitos (kiinteistörekisterikartta), Luonnonvarakeskus
(kantohinnat, monilähteinen VMI), SYKE Ryhti (rakennukset) – kaikki CC BY 4.0. Puuston arvo on laskennallinen, ei kauppahinta.
