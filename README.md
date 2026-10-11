# mappendium.com

Le site d'une page de **Mappendium**, un jeu idle calme où un petit robot parcourt le monde pour en
cataloguer chaque lieu. La page donne le jeu en deux lignes, le lien Steam, la déclaration de
confidentialité (en français et en anglais) et le contact.

*The one-page site of **Mappendium**, a calm idle game. The page gives the game in two lines, the Steam
link, the privacy statement (French and English) and the contact.*

- Une seule page, `index.html`, sans build, sans script, sans requête vers un tiers.
- Servie par GitHub Pages à <https://mappendium.com> (`CNAME`) ; `.nojekyll` évite tout traitement.
- **Pousser sur `main`, c'est publier** : la page est en ligne une minute plus tard.
- Toute modification de la déclaration change la date « Dernière mise à jour » et ajoute une ligne à
  l'historique, au bas de la page.

## Les fichiers

| Fichier | Ce que c'est |
|---|---|
| `index.html` | la page ; ses styles sont dedans |
| `mot.svg` | le mot MAPPENDIUM, composé (Fredoka, licence OFL) |
| `motif-large-sol.svg`, `sol.webp` | la mer de nuages et, dans l'ouverture, le vrai sol du jeu : une capture de Québec, étalonnée, ses épingles aux vrais lieux |
| `polices/` | IBM Plex Sans (400, 600) et Literata (600), sous-ensembles latins en WOFF2, avec leurs licences OFL à côté |

Les polices sont sous [SIL Open Font License 1.1](https://openfontlicense.org/) ; chaque licence est dans `polices/`.
Rien n'est généré par une IA : le mot et le motif sont tracés par script, le sol est une capture du jeu.

Contact : <contact@mappendium.com>
