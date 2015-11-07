# Base pour Front-End

Ce dépôt permet de complier des fichier .scss manuellement ou automatiquement ainsi que de rafraichir à chaque modification des fichiers html et css le navigateur.

Les plugins gulp installés sont les suivants :
- [gulp-sass](https://www.npmjs.com/package/gulp-sass)
- [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer)
- [gulp-size](https://www.npmjs.com/package/gulp-size)
- [browser-sync](https://www.npmjs.com/package/browser-sync)

# Installation :
Pour pouvoir utiliser la configuration il est nécessaire d'installer [nodejs](https://nodejs.org/), puis de taper la commande suivante dans une console :
`npm install -g gulp`. Vous disposerez alors de la commande `gulp`

Cloner le dépôt dans le répertoire voulu, et lancer la commande `npm install` dans ce même répertoire.

# Configuration :
1. browser-sync

# Utilisation :
- pour compiler les fichier .scss et rafraichir le navigateur : `gulp` 
- pour compiler les fichiers .scss manuellement : `gulp sass`
- pour compiler automatiquement les fichiers .scss : `gulp sass:watch`
- pour rafraichir le navigateur à chque modification des fichiers : `gulp server`