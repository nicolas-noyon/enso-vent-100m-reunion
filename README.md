# Influence d'El Niño (ENSO) sur le vent à 100 m à La Réunion

Travail pratique du **Master 2 Énergie (ENERGY-Lab, Université de La Réunion)**.
Partie 1 (indice Niño3.4) en binôme ; **partie 2 (vent à 100 m) et soutenance orale réalisées seul**.

## Objectif
Calculer l'indice **Niño3.4** à partir d'ERA5 et étudier son effet sur la **ressource éolienne à 100 m** autour de La Réunion, une hauteur proche de celle des moyeux d'éoliennes.

## Contenu
| Fichier | Description |
|---|---|
| [`partie1_indice_nino34.ipynb`](partie1_indice_nino34.ipynb) | Calcul de l'indice Niño3.4 |
| [`partie2_vent_100m.ipynb`](partie2_vent_100m.ipynb) | Vent à 100 m, anomalies et lien avec les phases El Niño / La Niña |
| [`fiche_resultats_vent_100m.pdf`](fiche_resultats_vent_100m.pdf) | Fiche de résultats de la partie 2 (vent à 100 m) |

## Données
Dans le dossier [`data/`](data/) :

| Fichier | Contenu |
|---|---|
| `mon_gl_sstg_1979-2001.nc`, `mon_gl_sstg_2002-2024.nc` | Température de surface de la mer, moyennes mensuelles ERA5 (globe) |
| `nino34.long.anom.csv` | Indice Niño3.4 de référence, anomalies mensuelles depuis 1870 ([NOAA PSL](https://psl.noaa.gov/data/timeseries/month/)) |

Le vent à 100 m (1991–2020) et le masque terre-mer utilisés dans la partie 2 sont dans le dépôt [era5-maurice-ressource-production/data](https://github.com/nicolas-noyon/era5-maurice-ressource-production/tree/main/data). Il faut les copier dans `data/` avant de lancer la partie 2.

**Source et licence ERA5 :** Generated using Copernicus Climate Change Service information [2026]. Ni la Commission européenne ni l'ECMWF ne sont responsables de l'usage qui est fait de ces données.
Référence : Hersbach, H. et al. (2023). *ERA5 monthly averaged data on single levels from 1940 to present.* C3S Climate Data Store. DOI : [10.24381/cds.f17050d7](https://doi.org/10.24381/cds.f17050d7)

## Outils
Python · xarray · pandas · NumPy · Matplotlib

## Lancer
```bash
pip install numpy pandas xarray netCDF4 matplotlib jupyter
jupyter notebook
```
Dans les notebooks, faire pointer la variable `DATA` vers le dossier [`data/`](data/).

## Auteur
Nicolas NOYON – nicolasnoyon.pro@gmail.com
