# oc-p3-ohmyfood
Dynamisez une page web avec des animations CSS

## Contexte
- Ohmyfood! jeune startup New York > Paris
- Site : menus de restaurants gastronomiques, menus personnalisés
- Cible : classes moyennes et supérieures, pressées

**L'équipe**
- Paul, le CTO du futur site ;
- Fanny, l’UX designer > couleurs de Paris ;
- Anissa, commerciale;
- Moi, dév junior du site

**Ressources**
- Brief avec Paul
- Maquettes mobile + animations
- Fonts : https://fonts.google.com/
- Déployer site sur github : https://www.youtube.com/watch?v=dBAZ5Qc2bIk
- Git : 
    - Grafikart (3h50) : https://grafikart.fr/formations/git
    - Git Expert (OC) : https://openclassrooms.com/fr/courses/7688581-devenez-un-expert-de-git-et-github
- Sass : https://www.grafikart.fr/formations/sass-preprocesseur
- Loading spinner : https://cssloaders.github.io/, https://codepen.io/collection/KLDEaD, https://www.youtube.com/watch?v=-HS9IIuT_Mo

**Livrables**
Projet3_abel_jerome.zip :
- Abel_Jerome_1_code_092022.txt : https://github.com/jeromeabel/jeromeabel.github.io
- Abel_Jerome_2_site_092022.txt : https://jeromeabel.github.io/

## Mission
- Responsive : mobile-first (maquette), tablet & desktop (free)
- Outils : Github, CSS (+ animations), SASS
- Accessibilité : Github Pages
- Validation W3C en HTML et CSS sans erreur
- Navigateurs Chrome et Firefox
- Pages : accueil + 4 menus
- Charte graphique fonts et couleurs

## Questions I
- github pages ? ou repo puis github pages ?
- git branches ? par fonctionnalité + merge ?
- utilisation de classes container ?
- breakpoints: 375px ou 750px ?
- header : box-shadow logo ?
- accueil - card : img alignement différent ?
- page menu : main au dessus de l'image du header : top:-125px ?
- page menu : anim button select : translateX en px... VS déplacement du texte en %

## Questions II
- anim. background > opacity (performances)
- logo image ou font ?
- fonts link ou sass import ?
- thème paris ?
- images responsive ? un seul dossier... > img ou picture
- apparition/disparition éléments ? Nouveau (card) + Arrow (header menu) > classes display none/block


## Setup Live Sass Compiler
```
"liveSassCompile.settings.generateMap": true,
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/css"
    }
  ]
```