# Projet 3: OhMyFood!
Troisième projet du parcours "Développeur web" chez OpenClassroom. L'objectif est d'intégrer le site en front-end en dynamisant les pages avec des animations CSS, tout en utilisant le préprocesseur Sass.

[[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNDIuODM5OTk5OTk5OTk5OTciIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAxNDIuODM5OTk5OTk5OTk5OTcgMzUiPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9IjAiIHk9IjAiIHdpZHRoPSI3Ny41MyIgaGVpZ2h0PSIzNSIgZmlsbD0iI0U0NkMxNyIvPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9Ijc1LjUzIiB5PSIwIiB3aWR0aD0iNjcuMzA5OTk5OTk5OTk5OTkiIGhlaWdodD0iMzUiIGZpbGw9IiMzQUMxRDAiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTUuNzAgMjJMMTQuMjIgMjJMMTQuMjIgMTMuNDdMMTUuNzAgMTMuNDdMMTUuNzAgMTcuMDJMMTkuNTEgMTcuMDJMMTkuNTEgMTMuNDdMMjAuOTkgMTMuNDdMMjAuOTkgMjJMMTkuNTEgMjJMMTkuNTEgMTguMjFMMTUuNzAgMTguMjFMMTUuNzAgMjJaTTI3LjQxIDE0LjY2TDI0Ljc4IDE0LjY2TDI0Ljc4IDEzLjQ3TDMxLjU0IDEzLjQ3TDMxLjU0IDE0LjY2TDI4Ljg4IDE0LjY2TDI4Ljg4IDIyTDI3LjQxIDIyTDI3LjQxIDE0LjY2Wk0zNi43OCAyMkwzNS4zMCAyMkwzNS4zMCAxMy40N0wzNy4yMiAxMy40N0wzOS42OCAyMC4wMUw0Mi4xNCAxMy40N0w0NC4wNSAxMy40N0w0NC4wNSAyMkw0Mi41OCAyMkw0Mi41OCAxOS4xOUw0Mi43MiAxNS40M0w0MC4yMCAyMkwzOS4xNCAyMkwzNi42MyAxNS40M0wzNi43OCAxOS4xOUwzNi43OCAyMlpNNTQuMTUgMjJMNDguNzkgMjJMNDguNzkgMTMuNDdMNTAuMjggMTMuNDdMNTAuMjggMjAuODJMNTQuMTUgMjAuODJMNTQuMTUgMjJaTTU4LjE2IDE5LjcwTDU4LjE2IDE5LjcwTDU5LjU0IDE5LjcwUTU5LjYyIDIwLjMyIDU5Ljk4IDIwLjY1UTYwLjM1IDIwLjk4IDYwLjkzIDIwLjk4TDYwLjkzIDIwLjk4UTYxLjU5IDIwLjk4IDYxLjk2IDIwLjUxUTYyLjMyIDIwLjA0IDYyLjMyIDE5LjIzTDYyLjMyIDE5LjIzUTYyLjMyIDE4LjQ2IDYxLjkyIDE4LjAwUTYxLjUxIDE3LjU1IDYwLjgxIDE3LjU1TDYwLjgxIDE3LjU1UTYwLjQyIDE3LjU1IDYwLjE1IDE3LjY1UTU5Ljg4IDE3Ljc1IDU5LjU2IDE4LjA1TDU5LjU2IDE4LjA1TDU4LjQzIDE3Ljc3TDU4Ljg5IDEzLjQ3TDYzLjQ3IDEzLjQ3TDYzLjQ3IDE0LjcwTDYwLjA3IDE0LjcwTDU5Ljg0IDE2Ljc0UTYwLjQzIDE2LjQwIDYxLjE3IDE2LjQwTDYxLjE3IDE2LjQwUTYyLjM5IDE2LjQwIDYzLjA3IDE3LjE4UTYzLjc1IDE3Ljk2IDYzLjc1IDE5LjI4TDYzLjc1IDE5LjI4UTYzLjc1IDIwLjU4IDYzLjAwIDIxLjM1UTYyLjI1IDIyLjEyIDYwLjk0IDIyLjEyTDYwLjk0IDIyLjEyUTU5Ljc3IDIyLjEyIDU5LjAwIDIxLjQ1UTU4LjIzIDIwLjc5IDU4LjE2IDE5LjcwWiIgZmlsbD0iI0ZGRkZGRiIvPjxwYXRoIGNsYXNzPSJzdmdfX3RleHQiIGQ9Ik04OS4yOSAxNy44MEw4OS4yOSAxNy44MFE4OS4yOSAxNi41NCA4OS44OSAxNS41NFE5MC40OSAxNC41NSA5MS41NCAxMy45OVE5Mi41OSAxMy40MyA5My45MSAxMy40M0w5My45MSAxMy40M1E5NS4wNiAxMy40MyA5NS45OCAxMy44NFE5Ni45MSAxNC4yNSA5Ny41MiAxNS4wMkw5Ny41MiAxNS4wMkw5Ni4wMSAxNi4zOVE5NS4yMCAxNS40MCA5NC4wMyAxNS40MEw5NC4wMyAxNS40MFE5My4zNCAxNS40MCA5Mi44MSAxNS43MFE5Mi4yOCAxNiA5MS45OCAxNi41NFE5MS42OSAxNy4wOSA5MS42OSAxNy44MEw5MS42OSAxNy44MFE5MS42OSAxOC41MSA5MS45OCAxOS4wNVE5Mi4yOCAxOS42MCA5Mi44MSAxOS45MFE5My4zNCAyMC4yMCA5NC4wMyAyMC4yMEw5NC4wMyAyMC4yMFE5NS4yMCAyMC4yMCA5Ni4wMSAxOS4yMkw5Ni4wMSAxOS4yMkw5Ny41MiAyMC41OFE5Ni45MSAyMS4zNSA5NS45OSAyMS43NlE5NS4wNiAyMi4xNyA5My45MSAyMi4xN0w5My45MSAyMi4xN1E5Mi41OSAyMi4xNyA5MS41NCAyMS42MVE5MC40OSAyMS4wNSA4OS44OSAyMC4wNVE4OS4yOSAxOS4wNiA4OS4yOSAxNy44MFpNMTAxLjQ3IDIxLjI0TDEwMS40NyAyMS4yNEwxMDIuMjUgMTkuNDlRMTAyLjgxIDE5Ljg2IDEwMy41NiAyMC4wOVExMDQuMzAgMjAuMzIgMTA1LjAyIDIwLjMyTDEwNS4wMiAyMC4zMlExMDYuMzkgMjAuMzIgMTA2LjM5IDE5LjY0TDEwNi4zOSAxOS42NFExMDYuMzkgMTkuMjggMTA2LjAwIDE5LjExUTEwNS42MSAxOC45MyAxMDQuNzUgMTguNzRMMTA0Ljc1IDE4Ljc0UTEwMy44MCAxOC41MyAxMDMuMTYgMTguMzBRMTAyLjUzIDE4LjA2IDEwMi4wNyAxNy41NVExMDEuNjIgMTcuMDMgMTAxLjYyIDE2LjE2TDEwMS42MiAxNi4xNlExMDEuNjIgMTUuMzkgMTAyLjA0IDE0Ljc3UTEwMi40NiAxNC4xNSAxMDMuMjkgMTMuNzlRMTA0LjEzIDEzLjQzIDEwNS4zMyAxMy40M0wxMDUuMzMgMTMuNDNRMTA2LjE2IDEzLjQzIDEwNi45NiAxMy42MlExMDcuNzcgMTMuODAgMTA4LjM5IDE0LjE3TDEwOC4zOSAxNC4xN0wxMDcuNjUgMTUuOTNRMTA2LjQ1IDE1LjI4IDEwNS4zMiAxNS4yOEwxMDUuMzIgMTUuMjhRMTA0LjYxIDE1LjI4IDEwNC4yOSAxNS40OVExMDMuOTcgMTUuNzAgMTAzLjk3IDE2LjA0TDEwMy45NyAxNi4wNFExMDMuOTcgMTYuMzcgMTA0LjM1IDE2LjU0UTEwNC43NCAxNi43MSAxMDUuNTkgMTYuODlMMTA1LjU5IDE2Ljg5UTEwNi41NSAxNy4xMCAxMDcuMTggMTcuMzNRMTA3LjgxIDE3LjU2IDEwOC4yNyAxOC4wN1ExMDguNzMgMTguNTggMTA4LjczIDE5LjQ2TDEwOC43MyAxOS40NlExMDguNzMgMjAuMjEgMTA4LjMxIDIwLjgzUTEwNy44OSAyMS40NCAxMDcuMDUgMjEuODBRMTA2LjIxIDIyLjE3IDEwNS4wMSAyMi4xN0wxMDUuMDEgMjIuMTdRMTAzLjk5IDIyLjE3IDEwMy4wMyAyMS45MlExMDIuMDcgMjEuNjcgMTAxLjQ3IDIxLjI0Wk0xMTIuNzIgMjEuMjRMMTEyLjcyIDIxLjI0TDExMy41MCAxOS40OVExMTQuMDYgMTkuODYgMTE0LjgxIDIwLjA5UTExNS41NSAyMC4zMiAxMTYuMjcgMjAuMzJMMTE2LjI3IDIwLjMyUTExNy42NCAyMC4zMiAxMTcuNjQgMTkuNjRMMTE3LjY0IDE5LjY0UTExNy42NCAxOS4yOCAxMTcuMjUgMTkuMTFRMTE2Ljg2IDE4LjkzIDExNi4wMCAxOC43NEwxMTYuMDAgMTguNzRRMTE1LjA1IDE4LjUzIDExNC40MSAxOC4zMFExMTMuNzggMTguMDYgMTEzLjMyIDE3LjU1UTExMi44NyAxNy4wMyAxMTIuODcgMTYuMTZMMTEyLjg3IDE2LjE2UTExMi44NyAxNS4zOSAxMTMuMjkgMTQuNzdRMTEzLjcxIDE0LjE1IDExNC41NCAxMy43OVExMTUuMzggMTMuNDMgMTE2LjU4IDEzLjQzTDExNi41OCAxMy40M1ExMTcuNDEgMTMuNDMgMTE4LjIxIDEzLjYyUTExOS4wMiAxMy44MCAxMTkuNjQgMTQuMTdMMTE5LjY0IDE0LjE3TDExOC45MCAxNS45M1ExMTcuNzAgMTUuMjggMTE2LjU3IDE1LjI4TDExNi41NyAxNS4yOFExMTUuODYgMTUuMjggMTE1LjU0IDE1LjQ5UTExNS4yMiAxNS43MCAxMTUuMjIgMTYuMDRMMTE1LjIyIDE2LjA0UTExNS4yMiAxNi4zNyAxMTUuNjAgMTYuNTRRMTE1Ljk5IDE2LjcxIDExNi44NCAxNi44OUwxMTYuODQgMTYuODlRMTE3LjgwIDE3LjEwIDExOC40MyAxNy4zM1ExMTkuMDYgMTcuNTYgMTE5LjUyIDE4LjA3UTExOS45OCAxOC41OCAxMTkuOTggMTkuNDZMMTE5Ljk4IDE5LjQ2UTExOS45OCAyMC4yMSAxMTkuNTYgMjAuODNRMTE5LjE0IDIxLjQ0IDExOC4zMCAyMS44MFExMTcuNDYgMjIuMTcgMTE2LjI2IDIyLjE3TDExNi4yNiAyMi4xN1ExMTUuMjQgMjIuMTcgMTE0LjI4IDIxLjkyUTExMy4zMiAyMS42NyAxMTIuNzIgMjEuMjRaTTEyMy42NyAyMS4zNEwxMjMuNjcgMjEuMzRMMTI0LjUzIDE5LjU1UTEyNS4wMyAxOS44OCAxMjUuNjQgMjAuMDdRMTI2LjI2IDIwLjI1IDEyNi44NyAyMC4yNUwxMjYuODcgMjAuMjVRMTI3LjQ4IDIwLjI1IDEyNy44NCAyMC4wMlExMjguMjAgMTkuNzkgMTI4LjIwIDE5LjM3TDEyOC4yMCAxOS4zN1ExMjguMjAgMTguNTUgMTI2LjkxIDE4LjU1TDEyNi45MSAxOC41NUwxMjUuOTIgMTguNTVMMTI1LjkyIDE3LjA1TDEyNy40MiAxNS40NEwxMjQuMTEgMTUuNDRMMTI0LjExIDEzLjYwTDEzMC4xOCAxMy42MEwxMzAuMTggMTUuMDlMMTI4LjQ0IDE2Ljk2UTEyOS40OCAxNy4xOCAxMzAuMDQgMTcuODJRMTMwLjYwIDE4LjQ2IDEzMC42MCAxOS4zN0wxMzAuNjAgMTkuMzdRMTMwLjYwIDIwLjExIDEzMC4xOSAyMC43NVExMjkuNzkgMjEuMzkgMTI4Ljk3IDIxLjc4UTEyOC4xNSAyMi4xNyAxMjYuOTQgMjIuMTdMMTI2Ljk0IDIyLjE3UTEyNi4wNSAyMi4xNyAxMjUuMTggMjEuOTVRMTI0LjMxIDIxLjc0IDEyMy42NyAyMS4zNFoiIGZpbGw9IiNGRkZGRkYiIHg9Ijg4LjUzIi8+PC9zdmc+)](https://forthebadge.com)](https://forthebadge.com/generator/?plabel=HTML5&slabel=CSS3&pbg=%23E46C17&sbg=%233AC1D0)

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