# Third-party notices

## Fonts (SIL Open Font License 1.1 — see `licenses/OFL.txt`)

| Font file (app and `web/fonts`) | Based on | Changes |
|---|---|---|
| `sans_regular.ttf`, `sans_semibold.ttf`, `sans_bold.ttf` | IBM Plex Sans © 2017 IBM Corp. | Subset to Latin + Cyrillic; renamed to “FPV Sans” because “Plex” is a Reserved Font Name |
| `mono_regular.ttf`, `mono_bold.ttf` | JetBrains Mono © 2020 The JetBrains Mono Project Authors | Subset to Latin + Cyrillic |
| `exo_semibold.ttf`, `exo_extrabold.ttf` | Exo 2 © 2013 The Exo 2 Project Authors | Instanced from the variable font, subset to Latin + Cyrillic |

## Libraries

- [osmdroid](https://github.com/osmdroid/osmdroid) — Apache License 2.0
- AndroidX / Jetpack Compose — Apache License 2.0
- [Leaflet](https://leafletjs.com) (web version) — BSD 2-Clause License, see `web/leaflet/LICENSE`

## Data and map tiles

- Weather: [Open-Meteo](https://open-meteo.com) — data under CC BY 4.0. Free API for non-commercial use.
- Reverse geocoding: [BigDataCloud](https://www.bigdatacloud.com) free client-side API.
- Maps: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors (ODbL);
  terrain style © [OpenTopoMap](https://opentopomap.org) (CC-BY-SA).
  Note: the public tile servers of OpenStreetMap have a usage policy; an app distributed
  to many users should use its own or a commercial tile provider.
