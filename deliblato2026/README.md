# Deliblato Sands 2026 — wildfire spread reconstruction, 5 August – 17 September 2026

*Srpska verzija je ispod. / Serbian version below.*

**Period analysed: 2026-08-05 10:51 – 2026-09-17 23:59 UTC** (5 August – 17 September 2026).
The period includes the reactivation of 5–7 September 2026 inside the burn area; the fire was localised on 15 September. Time of arrival records only the first arrival of fire, so re-burning of already burned ground appears in fire radiative power, not in the isochrones.

Static page with the results of a satellite-based reconstruction of wildfire
spread. Open `index.html` (SR/EN switch in the top-right corner) or the
published version on GitHub Pages. English versions of the pages, animation
and figures carry the `_en` suffix.

**Contents**

- `deliblato2026_frp_en.html` — Fire radiative power in time and space
- `deliblato2026_dashboard_en.html` — Fire behaviour dashboard
- `deliblato2026_animation_en.mp4` — Spread animation
- `deliblato2026_frp_animation_en.mp4` — FRP animation
- `deliblato2026_fire_behavior_en.png` — Rate of spread and area growth
- `deliblato2026_frp_max.png` — Maximum measured intensity

**Method.** The fire-spread reconstruction application was developed on the
basis of the methodology presented by Akli Benali (University of Lisbon) and
Marcos Campos (Força Especial de Proteção Civil) at the NERO Café webinar
*Practical tools to reconstruct wildfire spread* (May 2024, COST Action
CA22164 — NERO, European Network on Extreme Fire Behavior), and of the
published work of the same group, above all the PT-FireSprd database (Benali
et al., 2023). Fire arrival time is interpolated from thermal detections (NASA
FIRMS) and constrained by dated perimeters from Sentinel-2/3 imagery and the
manual Copernicus EMS delineation. Thermal detections (VIIRS, MODIS and the 10-min MTG FCI) also veto an optical “not yet burned” constraint where fire was detected before the image (smoke-obscured scenes). Burned area: 13,012 ha.

- Benali, A. & Campos, M. (2024). *Practical tools to reconstruct wildfire
  spread.* NERO Café webinar, COST Action CA22164 — NERO, European Network on
  Extreme Fire Behavior. https://nero-network.eu
- Benali, A., Guiomar, N., Gonçalves, H., Mota, B., Silva, F., Fernandes, P. M.,
  Mota, C., Penha, A., Santos, J., Pereira, J. M. C. & Sá, A. C. L. (2023). The
  Portuguese Large Wildfire Spread database (PT-FireSprd). *Earth System Science
  Data*, 15, 3791–3818. https://doi.org/10.5194/essd-15-3791-2023

**Data sources and attribution**

- Contains modified Copernicus Sentinel data (2026), processed by the authors.
- Thermal anomalies: NASA FIRMS (MODIS, VIIRS).
- MTG FCI fire radiative power (10 min): EUMETSAT LSA SAF (2025), MTG Fire Radiative Power - Pixel, V.1 (MTFRPPIXEL), accessed via EUMETView; CC BY 4.0.
- Final perimeter derived from the Copernicus EMS Rapid Mapping delineation
  (EMSR914). © European Union, Copernicus Emergency Management Service. Only
  derived vector layers are published; the very-high-resolution image
  background is not redistributed.
- Elevation: Copernicus DEM GLO-30.

[![Developed with Claude](https://img.shields.io/badge/Developed%20with-Claude-D97757?logo=claude&logoColor=white)](https://claude.ai)  
The application was developed with the assistance of Claude (Anthropic).

**Data.** Geospatial results (GeoPackage, TOA raster, metrics.csv) are not in
this repository because of their size — they are archived separately, with a
DOI.

---

# Deliblatska peščara 2026 — rekonstrukcija širenja požara, 5. 8. – 17. 9. 2026.

**Analizirani period: 2026-08-05 10:51 – 2026-09-17 23:59 UTC** (5 August – 17 September 2026).
Period obuhvata i reaktivaciju od 5–7. septembra 2026. unutar požarišta; požar je lokalizovan 15. septembra. Vreme dolaska vatre beleži samo prvi dolazak, pa se ponovno gorenje već izgorele površine vidi u snazi zračenja, a ne u izohronama.

Statična stranica sa rezultatima rekonstrukcije širenja požara iz satelitskih
podataka. Otvori `index.html` (prekidač SR/EN gore desno) ili objavljenu
verziju preko GitHub Pages. Engleske verzije stranica, animacije i grafikona
nose sufiks `_en`.

**Sadržaj**

- `deliblato2026_frp.html` — FRP kroz vreme i prostor
- `deliblato2026_dashboard.html` — Ponašanje požara — kontrolna tabla
- `deliblato2026_animacija.mp4` — Animacija širenja
- `deliblato2026_frp_animacija.mp4` — Animacija FRP-a
- `deliblato2026_fire_behavior.png` — Brzina širenja i rast površine
- `deliblato2026_frp_max.png` — Najveći izmereni intenzitet

**Metoda.** Aplikacija za rekonstrukciju širenja požara razvijena je na osnovu
metodologije koju su Akli Benali (University of Lisbon) i Marcos Campos (Força
Especial de Proteção Civil) predstavili na NERO Café webinaru *Practical tools
to reconstruct wildfire spread* (maj 2024, COST Action CA22164 — NERO), i
objavljenih radova iste grupe, pre svega baze PT-FireSprd (Benali i sar., 2023).
Vreme dolaska vatre interpolira se iz termalnih detekcija (NASA FIRMS), a
ograničava datiranim perimetrima iz Sentinel-2/3 snimaka i ručne delineacije
Copernicus EMS-a. Termalne detekcije (VIIRS, MODIS i MTG FCI na 10 min) poništavaju optičko „još nije gorelo“ tamo gde je vatra viđena pre snimka (scene pod dimom). Opožarena površina: 13.012 ha.

**Izvori i atribucija**

- Sadrži izmenjene Copernicus Sentinel podatke (2026), obrađene od strane autora.
- Termalne anomalije: NASA FIRMS (MODIS, VIIRS).
- MTG FCI snaga zračenja požara (10 min): EUMETSAT LSA SAF (2025), MTG Fire Radiative Power - Pixel, V.1 (MTFRPPIXEL), preko EUMETView-a; CC BY 4.0.
- Finalni perimetar izveden iz Copernicus EMS Rapid Mapping delineacije
  (EMSR914). © European Union, Copernicus Emergency Management Service.
  Objavljeni su samo izvedeni vektorski slojevi; podloga sa snimka vrlo visoke
  rezolucije nije redistribuirana.
- Nadmorska visina: Copernicus DEM GLO-30.

Aplikacija je razvijena uz pomoć Claude-a (Anthropic).

**Podaci.** Geoprostorni rezultati (GeoPackage, TOA raster, metrics.csv) nisu u
ovom repozitorijumu zbog veličine — arhiviraju se posebno, sa DOI-jem.
