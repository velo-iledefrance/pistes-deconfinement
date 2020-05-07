# Comment installer ce site pour sa ville ?

Et la réponse est simple : clone
1. crée un compte github, clone le projet https://github.com/velo-iledefrance/pistes-deconfinement
2. le site est dispo sur https://toncompte.github.io/coronapiste-website/
Oui c'est github qui héberge le site, c'est très léger ça ne pose pas de soucis.
En fait la page c'est juste une page html qui contient du code javascript (Leaflet) pour afficher les différents calques.
3. modifier les fichier .geojson à ta convenance (avec UMap ou http://geojson.io)
4. pointer le nom de domaine carte.trifouilly-les-oies-avelo.fr vers tontompte.github.io/coronapiste-website/

carte_de_travail_pistes_temporaires.geojson -> calque projet (gris)
existant.geojson -> itinéraire existant (rouge)
pistes_provisoires.geojson -> nouvelles pistes/itinéraires (orange)
