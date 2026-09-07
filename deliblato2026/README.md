# Deliblatska peščara 2026 — rekonstrukcija širenja požara, 5. – 28. 8. 2026.

**Analizirani period: 2026-08-05 10:51 – 2026-08-28 23:59 UTC** (5–28 August 2026).
Rekonstrukcija obuhvata isključivo taj period; kasnije reaktivacije istog
požarišta nisu uključene.

Statična stranica sa rezultatima rekonstrukcije širenja požara iz satelitskih
podataka. Otvori `index.html` ili objavljenu verziju preko GitHub Pages.

**Sadržaj**

- `deliblato2026_frp.html` — FRP kroz vreme i prostor
- `deliblato2026_dashboard.html` — Ponašanje požara — kontrolna tabla
- `deliblato2026_animacija.mp4` — Animacija širenja
- `deliblato2026_fire_behavior.png` — Brzina širenja i rast površine
- `deliblato2026_frp_max.png` — Najveći izmereni intenzitet

**Metoda.** Aplikacija za rekonstrukciju širenja požara razvijena je na osnovu
metodologije koju su Akli Benali (University of Lisbon) i Marcos Campos (Força
Especial de Proteção Civil) predstavili na NERO Café webinaru *Practical tools
to reconstruct wildfire spread* (maj 2024, COST Action CA22164 — NERO), i
objavljenih radova iste grupe, pre svega baze PT-FireSprd (Benali i sar., 2023).
Vreme dolaska vatre interpolira se iz termalnih detekcija (NASA FIRMS), a
ograničava datiranim perimetrima iz Sentinel-2/3 snimaka i ručne delineacije
Copernicus EMS-a. Opožarena površina: 12.344 ha.

- Benali, A. & Campos, M. (2024). *Practical tools to reconstruct wildfire
  spread.* NERO Café webinar, COST Action CA22164 — NERO, European Network on
  Extreme Fire Behavior. https://nero-network.eu
- Benali, A., Guiomar, N., Gonçalves, H., Mota, B., Silva, F., Fernandes, P. M.,
  Mota, C., Penha, A., Santos, J., Pereira, J. M. C. & Sá, A. C. L. (2023). The
  Portuguese Large Wildfire Spread database (PT-FireSprd). *Earth System Science
  Data*, 15, 3791–3818. https://doi.org/10.5194/essd-15-3791-2023

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
