# lola-relais

- `positions.json` : la meilleure position (aisstream.io, AISVesselTracker et Shiptrail lus en parallèle, sans doublon) des 60 dernières minutes, mise à jour à chaque nouvelle position (au plus toutes les 15 s).
- `sources.json` : toutes les lectures brutes des trois sources, horodatées (heure de la position) et nommées, pour les comparer.
Un seul commit, jamais d'historique. `positions.json` est lu par la page bac-lola (HTML-tools).
