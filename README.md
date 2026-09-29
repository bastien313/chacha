# 🦟 Une journée d'infirmière… piquante

Un petit dessin animé en 2D, en un seul fichier (`index.html`), sans aucune dépendance à installer.

**L'histoire** (environ 80 secondes) :

1. Le matin, l'infirmière quitte la maison (son mari lui fait coucou depuis la porte) et prend la voiture.
2. Arrivée à l'hôpital, elle entre dans la salle de soins… vérifie que personne ne regarde… et se transforme en **moustique** 🦟
3. Elle pique quatre patients endormis : à chaque piqûre, son ventre se remplit, le patient fait « Aïe ! » et une pièce
   file dans le compteur d'argent (en haut à droite). L'horloge accélère : la journée passe.
4. Le soir, elle reprend forme humaine, remonte en voiture et rentre.
5. Son mari l'attend à la porte : bisou, cœurs, gros plan. Fin, avec le salaire de la journée.

## Mettre la page en ligne (GitHub Pages)

1. Sur GitHub : **Settings → Pages**
2. *Build and deployment* → **Source : Deploy from a branch**
3. Choisir la branche (`main`, ou la branche qui contient `index.html`) et le dossier **/ (root)**, puis **Save**
4. Après ~1 minute, le lien apparaît en haut de la page : `https://<ton-pseudo>.github.io/chacha/`

C'est ce lien qu'il faut envoyer. Le fichier `.nojekyll` évite tout traitement inutile par GitHub.
Le navigateur bloque le son tant qu'on n'a pas touché la page : c'est pour ça qu'il y a un bouton
**Lancer l'histoire** au départ. Sur téléphone, mieux vaut tourner l'écran à l'horizontale.

## Commandes

| Action | Comment |
|---|---|
| Pause / reprendre | bouton ⏸, touche `Espace`, ou toucher l'image |
| Recommencer | bouton ↺ |
| Couper / remettre le son | bouton 🔊 |
| Aller directement à un instant (pratique pour tester) | `index.html?t=25` (en secondes, de 0 à ~80) |

## Personnaliser

Tout se règle au début du `<script>` de `index.html`, dans l'objet `CFG` :

| Réglage | Effet |
|---|---|
| `to` | dédicace affichée sur l'écran de fin (`''` pour l'enlever) |
| `amounts` | € gagnés à chaque piqûre (un montant par patient) |

Les durées de chaque scène sont dans l'objet `D` juste en dessous (`A` = départ, `B` = arrivée, `C` = hôpital,
`D` = départ du soir, `E` = retour à la maison).

## Tester en local

Ouvrir `index.html` dans un navigateur. Aucun build nécessaire.
