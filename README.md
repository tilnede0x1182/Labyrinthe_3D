# Labyrinthe_3D

## Technologies utilisées

- HTML5
- CSS3 (Grid, Flexbox)
- JavaScript ES6 (pur front-end, aucune dépendance)

## Fonctionnalités principales

- Sélecteur de taille N : cube 2 × 2 × 2 à 100 × 100 × 100
- Sélecteur de difficulté 1-10 :
  - 1 ⇒ ≥ 10 chemins possibles
  - 10 ⇒ chemin unique garanti
- Génération procédurale toujours solvable (algorithme carve-and-fill)
- Slider Z pour visualiser chaque couche horizontale
- Contrôles clavier :
  - Flèches = X-Y
  - Q = +Z, A = −Z
- Message de victoire affiché dans la page (aucune fenêtre d’alerte)

## Description

Ce projet permet d’explorer un labyrinthe 3D généré aléatoirement à l’intérieur d’un cube de taille N.
Le joueur visualise la structure interne via un curseur de couche Z, choisit la taille du cube et la densité des murs, puis tente d’atteindre la case but.
L’accent est mis sur : clarté visuelle, navigation spatiale intuitive, et simplicité technique (HTML + CSS + JS seulement).
