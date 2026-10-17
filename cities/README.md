# Villes (ciel de l'accueil d'Illiyun)

`cities.json.gz` : villes de plus de 5 000 habitants (nom, nom arabe, pays,
coordonnées, population, formes de recherche), triées par population.
`manifest.json` : empreinte du fichier (l'app ne le retélécharge que s'il change).

Construit par `tools/cities-data/build.py` (dépôt qurapp).

Sources : [GeoNames](https://www.geonames.org/) (CC BY 4.0), noms des pays
[i18n-iso-countries](https://github.com/michaelwittig/node-i18n-iso-countries) (MIT).
