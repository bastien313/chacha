# ❤ Pour Charlène

Une page web interactive, en un seul fichier (`index.html`), sans dépendance à installer.

**Le scénario** : un petit cœur → on appuie pour le faire battre (il grossit, se fissure et laisse
échapper de petits nageurs roses) → il explose → la Roue de la Fortune de l'Amour apparaît →
récompense : *« Turlututu chapeau pointu ! »* et un chapeau de fête.

## Mettre la page en ligne (GitHub Pages)

1. Sur GitHub : **Settings → Pages**
2. *Build and deployment* → **Source : Deploy from a branch**
3. Choisir la branche (`main`, ou la branche où se trouve `index.html`) et le dossier **/ (root)**, puis **Save**
4. Après ~1 minute, le lien apparaît en haut de la page : `https://<ton-pseudo>.github.io/chacha/`

C'est ce lien qu'il faut envoyer. Astuce : sur téléphone, mettre le son 🔊 (les bruitages sont générés
directement par le navigateur).

## Personnaliser

Tout se règle au début du `<script>` de `index.html`, dans l'objet `CFG` :

| Réglage | Effet |
|---|---|
| `taps` | nombre d'appuis avant l'explosion (15 par défaut) |
| `reward` | texte de la récompense |
| `letter` / `signature` | le petit mot d'amour affiché à la fin |
| `wheel` | les textes « incompréhensibles » de la roue |
| `winIndex` | la case sur laquelle la roue s'arrête |

## Tester en local

Ouvrir `index.html` dans un navigateur. Aucun build nécessaire.
