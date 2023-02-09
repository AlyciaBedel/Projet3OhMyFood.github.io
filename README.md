# Projet 3: OhMyFood!
Troisième projet du parcours "Développeur web" chez OpenClassroom. L'objectif est d'intégrer le site en front-end en dynamisant les pages avec des animations CSS, tout en utilisant le préprocesseur Sass.

![html5-css3](https://user-images.githubusercontent.com/98737248/217797596-12efd51e-5a28-4003-94b5-17dafda69ec2.svg)

#### Visualiser le site ici [https://alyciabedel.github.io/ohmyfood/]

![screenshot](https://user-images.githubusercontent.com/98737248/201363460-4f94b6e7-ddb8-4d2d-ac4e-b8ab3afaf4cc.png)

## Qui est OhMyFood ?
Ohmyfood! est une entreprise de commande de repas en ligne. Le concept est de permettre aux utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les restaurants partenaires car leur menu est préparé à l’avance. 

## Objectifs

1. Développer un site proposant le menu de 4 grands restaurants parisiens.
2. Permettre la réservation en ligne et la composition de menus.

## Technologies
- Utilisation de HTML5, CSS3 et du préprocesseur SASS. 
- Interdiction d'utiliser JavaScript ou un framework.

## Compatibilité
La cible étant les personnes connectées et pressées, le site sera développé en utilisant l’approche mobile-first. Sur tablette et desktop, le site devra s’adapter.

## Contenu des pages

### Page d'accueil
- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

### Pages de menu
- 4 pages contenant chacune le menu d’un restaurant.

### Header
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

### Footer
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

## Effets graphiques
### Boutons
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic

### Page d’accueil
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

### Pages de menu
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.

## Identité graphique
### Polices
- Logo et titres: Shrikhand
- Texte: Roboto

### Icônes
- Font Awesome [https://fontawesome.com/]

### Couleurs
- Primaire #9356DC 
- Secondaire #FF79DA 
- Tertiaire #99E2D0
