# Notes de développement

## Environnement de développement
### Atom
Comme Erbi code sur Atom je me suis dit que j'utiliserais cet éditeur moi aussi.
Voici la liste des plugins que j'utilise :
- [emmet](https://atom.io/packages/emmet) : simplifie l'écriture de HTML
- [atom-live-server](https://atom.io/packages/atom-live-server) : rechargement automatique de la page dès que le fichier HTML est sauvegardé
- [markdown-writer](https://atom.io/packages/markdown-writer) : simplifie l'écriture de Markdown (ce fichier)

## Démarrage du projet
### _From scratch_ :wink:
J'ai décidé de coder cette page _from scratch_, c'est à dire que je ne vais pas
utiliser de _template_ avancé avec un menu de navigation ou une grille déjà
définie, mais plutôt suivre la documentation de Bootstrap pas à pas pour arriver
au résultat désiré.

Au passage, en reprenant le fichier de Erbi je me suis rendu compte qu'il me
manquait le fichier CSS `tentativ.css`, donc il me manque quelques infos sur
l'esthétisme vraiment voulu, mais je vais faire ça de mémoire. Aussi, la barre
de navigation utilise des classes _non-bootstrap-iennes_ qui semblent venir
de la page [http://epicadesign.fr/creer-un-site-one-page-la-navigation/]().
Ce n'est peut-être qu'un détail, mais ici je vais plutôt tenter de tout faire
avec _Bootstrap_

### Cahier des charges
- Une page unique
- Chacun des blocs correspond à un slide
  - qui prend toute la largeur de la page
  - et si possible la hauteur aussi
  - avec une image de fond la couvrant totalement
- Le menu de navigation
  - en haut de la page
  - fixe
  - contient un lien vers chaque slide


### Getting started
Dans la documentation de Bootstrap, [un _template_ de base est donné](http://getbootstrap.com/docs/4.1/getting-started/introduction/#starter-template),
c'est celui que j'utiliserai :
```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>
```

- dire des choses sur le box-sizing :
  - http://getbootstrap.com/docs/4.1/getting-started/introduction/#box-sizing
  - https://css-tricks.com/box-sizing/
- http://getbootstrap.com/docs/4.1/content/reboot/
- http://getbootstrap.com/docs/4.1/layout/overview/#containers
- https://www.w3schools.com/tags/tag_main.asp
- https://www.w3schools.com/tags/tag_header.asp
