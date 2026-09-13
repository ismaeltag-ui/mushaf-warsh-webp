# mushaf-warsh-webp

Les 604 pages du mushaf de tajwid **en Warsh**, calées sur le cadre des pages
Hafs, pour un usage mobile.

Ce dépôt ne sert qu'à héberger des images destinées à être chargées par
[CoranRevise](https://coranrevise.expo.app). Il n'y a pas de code.

## Pourquoi elles sont produites plutôt que reprises

Il n'existe, à la connaissance de ce projet, **aucun jeu public de pages du
mushaf en Warsh accompagné de coordonnées mot par mot**. C'est ce que documente
`RECHERCHE-MUSHAFS.md` dans le dépôt de l'application, et qu'une recherche web
approfondie menée le 13 septembre 2026 a confirmé.

La solution ne consistait pas à chercher ailleurs mais à remarquer une chose :
**Dar al-Maarifah compose son édition en Warsh sur la grille de son édition en
Hafs** — mêmes pages, mêmes coupures de ligne, mêmes mots aux mêmes places. Les
83 881 rectangles de mots dont dispose déjà l'application valent donc pour les
deux. Ce n'est pas vrai du mushaf de Médine en Warsh, qui coupe ses lignes
ailleurs : c'est l'éditeur, et non la lecture, qui décide de la composition.

## Ce qui a été fait

Le scan d'origine fait 2520 × 3858 par page, cadre décoratif, bandeau de titre et
pied de page compris. Chaque page a été :

1. **détourée** de son cadre imprimé, dont le bord intérieur est rigoureusement le
   même sur les 604 pages — le scan vient d'un original numérique ;
2. **calée** sur le cadre 1340 × 1890 des pages Hafs, en cherchant la
   transformation qui fait coïncider les profils d'encre des deux éditions ;
3. **teintée** de la couleur de papier de l'application (`#FBF7EC`), pour que les
   masques posés par la Mémorisation s'y fondent sans laisser de rectangle ;
4. encodée en **WebP qualité 88**. Le sans-perte n'aurait conservé que le bruit du
   JPEG d'origine — 546 Ko la page contre 268, pour un écart moyen de 1,7 niveau
   sur 255, invisible.

Les deux pages d'ouverture, entièrement encadrées d'enluminures, sont calées
autrement : sur leurs bandes de texte, appariées à celles du Hafs.

## Contrôle

Mesure sur les 604 pages : **98 % de l'encre d'une page tombe dans un rectangle
de mot**, contre 100 % pour la page Hafs de référence. Médiane du rapport entre
les deux : 0,988.

## Provenance et licence

Images tirées du mushaf de tajwid de **Dar al-Maarifah** en Warsh (voie
d'al-Azraq), numérisé sur Internet Archive sous l'identifiant
[`Warsh_Azraq`](https://archive.org/details/Warsh_Azraq), qui ne porte aucune
mention de licence. L'œuvre est celle de Dar al-Maarifah ; ce dépôt n'en
revendique aucun droit et se borne à en proposer un ré-encodage destiné à un
usage personnel de mémorisation.
