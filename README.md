# Les Pages du Destin — jeu d'aventure à choix multiples

TP Initiation Web (HTML / CSS). Jeu d'aventure textuel ramifié : le héros avance de page en page en faisant des choix.
Univers inspiré de *Black Clover* (Royaume de Thistle, grimoires, Chevaliers Mages).

## Lancer le jeu

Ouvrir `index.html` dans un navigateur, puis cliquer sur « Commencer la lecture ». 

## Structure du projet

```
Germanicus-tp-web/
├── index.html               # Page d'accueil
├── style.css                # CSS principal (mise en page, boutons, animation de couverture)
├── backgrounds.css          # Un fond d'ambiance par scène (CSS + SVG intégré)
├── troll.css                # Style des pages « surprise » (vidéo plein écran)
├── pages/
│   ├── scene-initial.html   # Introduction + premier choix
│   ├── scene01-x … scene05-x.html
│   ├── sceneFin-*.html      # 4 fins
│   └── pageTroll*.html      # 5 pages surprise (vidéo)
├── assets/                  # Images et vidéos
├── arbre-navigation.pdf     # Arbre de navigation (document obligatoire)
└── README.md
```

## Contenu

- 30 pages HTML interconnectées (1 accueil, 1 introduction, 19 scènes, 4 fins, 5 pages surprise).
- Chaque scène : titre, fond d'ambiance, texte narratif, boutons de choix.
- Boutons personnalisés (classe `.btn`) avec icônes ; boutons-images (retour à l'accueil, boutons surprise).
- Animation CSS d'ouverture de livre sur les trois scènes de départ.
- Bonus : animations CSS, JavaScript (activation du son des vidéos).

## Chemins de l'histoire

Le plan complet des chemins possibles est dans `arbre-navigation.pdf`.
