Site web vitrine pour présenter le projet de la rue de Toulouse

## Lancer le projet

C’est un projet [Hugo](https://gohugo.io) utilisant le thème [Hugo Story](https://github.com/caressofsteel/hugo-story)

Vous aurez besoin d’une installation de [Hugo](https://gohugo.io)

Après avoir cloné le repository il faut télecharger le thème :

```bash
git submodule update --init --remote --recursive
```

Pour lancer le projet :

```bash
hugo serve
```

Ouvrez [http://localhost:1313](http://localhost:1313) dans votre navigateur pour voir le résultat.

## Où modifier le contenu

- les textes sont dans le dossier `data` chaque fichier `.yml` correspondant à une partie du site
- les images sont dans le dossier `static/images`
