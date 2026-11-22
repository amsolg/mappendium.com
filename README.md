# mappendium.com

Le site de **Mappendium**, un jeu idle calme où votre robot parcourt le monde pour en cataloguer chaque
lieu. L'accueil donne le jeu en deux lignes, le lien Steam, la déclaration de confidentialité (en français
et en anglais) et le contact ; `/donnees`, les bases du jeu sous ODbL.

*The site of **Mappendium**, a calm idle game where your robot roams the world to catalog every place in
it. The home page gives the game in two lines, the Steam link, the privacy statement (French and English)
and the contact; `/donnees`, the game's databases under the ODbL.*

- Des pages fixes (`index.html`, `donnees/`, `404.html`), sans build, sans script, sans requête vers un tiers.
- Servie par GitHub Pages à <https://mappendium.com> (`CNAME`) ; `.nojekyll` évite tout traitement.
- **Pousser sur `main`, c'est publier** : la page est en ligne une minute plus tard.
- Toute modification de la déclaration change la date « Dernière mise à jour » et ajoute une ligne à
  l'historique, au bas de la page.

## Les fichiers

| Fichier | Ce que c'est |
|---|---|
| `index.html` | la page ; ses styles sont dedans |
| `mot.svg` | le mot MAPPENDIUM, composé (Fredoka, licence OFL) |
| `sol.webp` | dans l'ouverture de la mer de nuages (le motif, écrit dans `index.html`), le vrai sol du jeu : une capture de Québec, étalonnée, ses épingles aux vrais lieux |
| `donnees/index.html` | la page des bases du jeu, sous ODbL |
| `404.html` | la page d'une adresse inconnue |
| `partage.jpg` | l'image d'un lien partagé : Québec et le fleuve découverts, vus de haut dans le jeu |
| `favicon-32.png`, `apple-touch-icon.png` | l'épingle de l'onglet, en image, pour Safari et l'écran d'accueil d'un téléphone |
| `polices/` | IBM Plex Sans (400, 600) et Literata (600), sous-ensembles latins en WOFF2, avec leurs licences OFL à côté |

Les polices sont sous [SIL Open Font License 1.1](https://openfontlicense.org/) ; chaque licence est dans `polices/`.
Rien n'est généré par une IA : le mot et le motif sont tracés par script, le sol et l'image de partage sont des captures du jeu.

Contact : <contact@mappendium.com>
