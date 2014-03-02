# Je veux ma télévision (française)

[décrire ici le but, les tenants et les aboutissants du projet]

## Licence

Voir la fichier [LICENCE](/LICENSE)

## Démarrage

Ce projet utilise [yeoman](yeoman.io/gettingstarted.html), [bower](http://bower.io/) et [grunt.js](http://gruntjs.com/). Il est recommandé d'installer les 3 ( l'installation de yeoman installe l'ensemble des logiciels ). Cependant seul bower et grunt sont necessaire.

**Yeoman** est un outil de bootstraping pour démarrer rapidement un projet.  
**bower** est un gestionnaire de dépendance ( JS , CSS, ...).  
**grunt.js** est un gestionnaire de serveur de test et compilateur supportant les test unitaire et fonctionnels.

### Travail sur le projet 

1. Cloner le projet
2. Dans un terminal tapez `bower install` pour télécharger les dépendances necessaires.
3. Dans un terminal tapez `grunt serve` pour afficher le site dans votre navigateur avec rafraichissement au moindre changement des fichiers sources
4. Editez les fichiers dans `app/`

### Compilation & mise en ligne

Dans un terminal tapez `grunt` pour compiler l'ensemble du projet. Un dossier `dist` sera créé avec tout ce qui devra être mis en ligne.

## Rapport de bug & contribution

Avant tout rapport de bug merci de consulter la [liste des bugs](https://github.com/PartiPirate/jeveuxmatelevision/issues?page=1&state=open). N'hesitez pas à nous remonter un [nouveau bug](https://github.com/PartiPirate/jeveuxmatelevision/issues/new). 

Si vous souhaitez contribuer mais n'avez pas d'accès au dépot, vous pouvez toujours cloner ce dépot et nous envoyer une push request. **Attention**, le code doit passer les test ( `grunt test` ).
