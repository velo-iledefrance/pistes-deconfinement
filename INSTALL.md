# Comment installer ce site pour sa ville ?

Réponse : clone
1. créer un compte github, cloner le projet https://github.com/velo-iledefrance/pistes-deconfinement
2. le site est dispo sur https://votrecompte.github.io/coronapiste-website/
C'est github qui héberge le site, c'est très léger ça ne pose pas de soucis.
La page c'est juste une page html qui contient du code javascript (Leaflet) pour afficher les différents calques.
Attention la branche qui contient le code du site est `gh-pages`, pas `master` !
3. modifier les fichier .geojson à votre convenance (avec UMap ou http://geojson.io)
4. pointer le nom de domaine carte.trifouilly-les-oies-avelo.fr vers votretompte.github.io/coronapiste-website/

carte_de_travail_pistes_temporaires.geojson -> calque projet (gris)
existant.geojson -> itinéraire existant (rouge)
pistes_provisoires.geojson -> nouvelles pistes/itinéraires (orange)
