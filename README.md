Cote v8 : Magic, Pokémon, Lorcana, Altered, Riftbound

MISE EN LIGNE
1. Gardez ces deux fichiers ensemble, dans le même dossier :
   - index.html          (l'application)
   - altered-index.json  (liste des cartes Altered Communes et Rares)
2. Sur Netlify, ouvrez votre site, onglet Deploys, puis déposez le dossier
   (ou ce fichier zip) dans la zone de dépôt. L'adresse ne change pas.

POINTS À SAVOIR
- Sans altered-index.json, Magic, Pokémon, Lorcana et Riftbound fonctionnent,
  mais pas la recherche Altered.
- L'application doit être ouverte depuis un site (Netlify) et non en double-cliquant
  sur le fichier : le navigateur bloque la lecture de altered-index.json en local.
- Altered et Riftbound : le prix de base est saisi à la main (aucune source
  de prix automatique autorisée). Les prix saisis sont mémorisés dans le navigateur.
- Lorcana : prix TCGplayer en dollars (Lorcast), convertis en euros.
- Le scan photo reste réservé à Magic et Pokémon.
- altered-index.json date du 31/10/2026 (base communautaire des cartes Altered,
  licence MIT). Les sets sortis ensuite n'y figurent pas.
