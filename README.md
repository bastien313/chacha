# La vraie vie de Charlène

Un petit dessin animé en 2D, en un seul fichier (`index.html`), sans aucune dépendance.
Le scénario est une surprise : il vaut mieux le découvrir en le regardant.

## En ligne (GitHub Pages)

La page est publiée depuis la branche `claude/loving-galileo-lxldyb` (dossier racine) :
https://bastien313.github.io/chacha/

## Commandes

| Action | Comment |
|---|---|
| Pause / reprendre | bouton ⏸, touche `Espace`, ou toucher l'image |
| Recommencer | bouton ↺ |
| Couper / remettre le son | bouton 🔊 |
| Aller directement à un instant (pour tester) | `index.html?t=25` (en secondes, de 0 à ~92) |

Sur téléphone, mieux vaut tourner l'écran à l'horizontale et mettre le son.

## Personnaliser

Au début du `<script>` de `index.html`, l'objet `CFG` : `to` (le prénom, utilisé dans le titre et l'écran de fin)
et `amounts` (les montants gagnés). Les durées des scènes sont dans l'objet `D`.
