# Deliblatska pescara 2026 — rekonstrukcija širenja požara

Statična stranica sa rezultatima rekonstrukcije širenja požara iz satelitskih
podataka. Otvori `index.html` ili objavljenu verziju preko GitHub Pages.

**Sadržaj**

- `deliblato2026_frp.html` — FRP kroz vreme i prostor
- `deliblato2026_dashboard.html` — Ponašanje požara — kontrolna tabla
- `deliblato2026_animacija.mp4` — Animacija širenja
- `deliblato2026_fire_behavior.png` — Brzina širenja i rast površine
- `deliblato2026_frp_max.png` — Najveći izmereni intenzitet

**Metoda.** NERO metodologija (Benali & Campos, COST Action CA22164): vreme
dolaska vatre interpolira se iz termalnih detekcija (NASA FIRMS), a ograničava
datiranim perimetrima iz Sentinel-2/3 snimaka i ručne delineacije Copernicus
EMS-a. Opožarena površina: 5.402 ha.

**Izvori i atribucija**

- Sadrži izmenjene Copernicus Sentinel podatke (2026), obrađene od strane autora.
- Termalne anomalije: NASA FIRMS (MODIS, VIIRS).
- Finalni perimetar izveden iz Copernicus EMS Rapid Mapping delineacije
  (EMSR914). © European Union, Copernicus Emergency Management Service.
  Objavljeni su samo izvedeni vektorski slojevi; podloga sa snimka vrlo visoke
  rezolucije nije redistribuirana.
- Nadmorska visina: Copernicus DEM GLO-30.

**Podaci.** Geoprostorni rezultati (GeoPackage, TOA raster, metrics.csv) nisu u
ovom repozitorijumu zbog veličine — arhiviraju se posebno, sa DOI-jem.
