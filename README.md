# Metsakartta

Talokartan metsätilat: kiinteistöt, joilla on metsämaata yli 2 ha, puuston laskennallinen arvo, puusto, ikärakenne ja
metsäpohja avoimista aineistoista. Tämä repositorio **ajaa ja julkaisee** metsätilojen karttatiedostot; ohjelmakoodi,
asetukset ja ohjeet ovat Talokartta-repositoriossa:

- Koodi: [vv-tec/Talokartta](https://github.com/vv-tec/Talokartta) – `pipeline/metsa.py`, esikatselusivu `metsa_web/`
- Kehittäjän muistio: Talokartan `CLAUDE.md` (tiekartan kohta 6) · omistajan ohje: Talokartan `KAYTTOOHJE.md`
- Julkaisu: https://vv-tec.github.io/Metsakartta/ (esikatselu) ja `data/` (karttatiedostot, joita Talokartta käyttää)
- Ajo: Actions → **Päivitä metsätilat ja julkaise** (joka aamu noin klo 6.47 ja käsin). Tarvitsee salaisuuden `MML_API_KEY`.

Lähteet: Suomen metsäkeskus (metsävaratieto), Maanmittauslaitos (kiinteistörekisterikartta), Luonnonvarakeskus
(kantohinnat), SYKE Ryhti (rakennukset) – kaikki CC BY 4.0. Puuston arvo on laskennallinen, ei kauppahinta.
