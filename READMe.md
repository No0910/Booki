# Booki !
## _Transformez une maquette en site web avec HTML & CSS_


![Build Status](https://badge.buildkite.com/sample.svg?status=passing)

1er projet de la formation de développeur web d'OpenClassroom.

![Screenshot du site avec aperçu des pages desktop et mobiles]

## Enjeux
---
- Intégrer l'interface du site avec du code HTML et CSS à partir d'une maquette.
- Permettre la réservation en ligne et la composition de menus.

## Livrables attendus
---
- Un fichier “index.html” contenant l’ensemble du code HTML du projet ;
- Un dossier “CSS” comprenant un fichier “style.css” contenant l’ensemble du code CSS du projet ;
- Un dossier “images” contenant l’ensemble des images utilisées.

### Intégration de contenu d'après maquettes

- Une page d'accueil en version desktop
- Adaptation en version tablette et mobile de la page d'accueil (Implémentation responsive)

### Spécifications techniques du projet

**Formulaire de recherche**
- Les usagers pourront rechercher des hébergements dans la ville de leur choix.
- Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être
édité par l’utilisateur.
- Il faut englober ce champ dans un formulaire. La partie Recherche ne doit pas
être fonctionnelle - il s’agit d’une première version pour valider l’interface.
-  Attention au style de la barre de recherche : sur desktop, le bouton de
recherche comprend le texte “Rechercher”, alors que sur mobile, c’est
une loupe. Pour gérer cela, il a fallu intégrer les deux éléments (le mot
+ l’icône) en HTML
- Ne pas appliquer une bordure sur l’intégralité du champ de
recherche, pour que le visuel corresponde à la maquette.

**Carte Hébergements et Activités**
- Chaque carte d’hébergement ou d’activité devra être cliquable dans son
intégralité (pas uniquement le titre).
- Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour
simuler la présence d’un lien.

**Filtres de recherche**
- Les hébergements peuvent être filtrés par thématique, comme le budget ou
l’ambiance.
- Les filtres doivent changer d’apparence au survol. Par contre, ils ne doivent pas
être fonctionnels - il s’agit d’une première version pour valider l’interface.

**Liens "Hébergements" et "Activités"**
- Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils
doivent mener respectivement vers la section “Hébergements à Marseille” et
“Activités à Marseille. 
- Au survol: Barre latérale doit apparaitre au dessus des titres en version Desktop, et en dessous en version Mobile.

**Breakpoint**
● >=992 px pour les écrans d’ordinateurs ;
● >=768 px pour les tablettes ;
● et tout ce qui est en dessous de 768 pour les téléphones portables

**Largeur Max**
Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer
une largeur maximum de 1 400 px.

**Desktop First**
Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first),
puis les tablettes et enfin les téléphones. L’utilisation des Media Queries nous permettra
de réaliser l’intégration pour les différents supports.

## Technologies utilisées
---
- [HTML] - Version 5
- [CSS] - Version 3
- [VScode] - Editeur de code
- [FontAwesome] - Bibliothèque d'icônes
- [GoogleFonts] - Bibliothèque de polices

## Identité graphique et contraintes techniques
---
**Polices de caractères**
- Raleway

**Couleurs utilisées**
- Bleu : #0065FC
- Bleu + clair : #DEEBFF
- Gris : #F2F2F2


**Compatibilité**
- Développement en Desktop-first à partir des maquettes fournies
- Responsive design intégré sur tout supports
- Validation HTML et CSS du W3C
- Dernières versions de Chrome, Firefox, Edge

**Validité du code**
- Le code doit être valide aux validateurs W3C HTML et CSS.
- Le code HTML ne doit pas contenir de propriété CSS.
- Lors du passage du desktop au mobile et à la tablette, ne pas dupliquer le code
HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la
loupe).
- Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser
le nom de l’élément lui-même.
- Ne pas dupliquer des classes CSS inutilement. Exemple : si 4 éléments sont
identiques du point de vue de la mise en forme, alors utiliser une seule et même
classe CSS, et non pas 4

## Installation
---
Une version en ligne est directement accessible à l'adresse : [Booki](https://nd-booki.netlify.app/)

Sinon, vous pouvez cloner le projet
```terminal
git clone https://github.com/No0910/Booki.git
```
