# Dati di PeakApp

Pacchetti scaricati dall'app **PeakApp** (riconoscimento delle montagne con la fotocamera):
cime, località e terreno delle Alpi italiane e dei dintorni, divisi in celle di 1°×1°.

I file si trovano nelle [release](../../releases): l'app scarica sempre l'ultima.

| File | Contenuto |
|---|---|
| `index.json` | elenco delle zone e dei file, con dimensione e impronta SHA-256 |
| `peaks_N46E011.json` | cime della cella (da OpenStreetMap) |
| `loc_N46E011.json` | località: paesi, comprensori sciistici, passi, rifugi (da OpenStreetMap) |
| `dem30_N46E011.pkd` | terreno a 30 m (Copernicus DEM GLO-30), formato a blocchi compressi |
| `dem90_N46E011.pkd` | terreno a 90 m (Copernicus DEM GLO-90), stesso formato |
| `aliases.json` | nomi alternativi di alcune cime (es. Nevegal → Col Visentin) |

## Licenze e attribuzioni

- **Cime e località**: © OpenStreetMap contributors, disponibili con licenza
  [Open Database License (ODbL)](https://www.openstreetmap.org/copyright).
  Questi file sono un database derivato e sono distribuiti con la stessa licenza ODbL.
- **Terreno**: Copernicus DEM GLO-30 e GLO-90, © DLR e.V. 2010-2014 e © Airbus Defence and Space GmbH
  2014-2018, forniti nell'ambito di COPERNICUS dall'Unione Europea e dall'ESA; tutti i diritti riservati.
  Dati elaborati (conversione di formato, compressione senza perdite).
