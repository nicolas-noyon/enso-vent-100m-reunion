# Influence d'El Niño (ENSO) sur le vent à 100 m à La Réunion

Travail pratique du **Master 2 Énergie (ENERGY-Lab, Université de La Réunion)**.
Partie 1 (indice Niño3.4) en binôme ; **partie 2 (vent à 100 m) et soutenance orale réalisées seul**.

## Objectif
Calculer l'indice **Niño3.4** à partir d'ERA5 et étudier son effet sur la **ressource éolienne à 100 m** autour de La Réunion, une hauteur proche de celle des moyeux d'éoliennes.

## Contenu
| Fichier | Description |
|---|---|
| `partie1_indice_nino34.ipynb` | Calcul de l'indice Niño3.4 |
| `partie2_vent_100m.ipynb` | Vent à 100 m, anomalies et lien avec les phases El Niño / La Niña |
| `figures/` | Cartes et séries temporelles |

## Outils
Python · xarray · pandas · NumPy · Matplotlib

## Lancer
```bash
pip install numpy pandas xarray netCDF4 matplotlib jupyter
jupyter notebook
```
Données ERA5 non incluses : [Copernicus Climate Data Store](https://cds.climate.copernicus.eu/).

## Auteur
Nicolas NOYON – nicolasnoyon.pro@gmail.com
