# Challenge intégration + Github
Jusqu'à maintenant, pour la plupart, vous travailliez seul(e) sur votre repo github. Vous étiez seul(e) à faire des commit, des push, etc. Aujourd'hui, vous allez faire en équipe :)

Vous allez devoir réaliser une page d'accueil à partir du modèle illustré par *template.png*. Ce modèle est un schéma (*wireframe, gabarit, mockup*) décrivant les positionnements et les éléments à avoir dans la page au minimum. 

Le sujet de ce site est **la domotique**.

**Vous serez en binômes et vous devrez collaborer sur le même repo github !**  Par exemple, l'un s'occupera d'aller chercher le contenu et de l'insérer tandis que l'autre s'occupera de la mise en page. 

**Chacun sera sur son ordi ! et vous devez pas être à côté**

Partagez-vous le travail équitablement. Il n'y a aucun intérêt s'il n'y a qu'un(e) seul(e) qui fait tout !

## Contraintes
* Le site devra être responsive
* La police utilisée est [Open Sans](https://www.google.com/fonts/specimen/Open+Sans)
* Les couleurs disponibles sont : du violet #7c2c8a et du gris.
* Vos frameworks devront être installer avec *bower*
* Vous ne devez pas travailler directement sur la branche master. Vous devez créer une autre branche en local, y faire vos modifications et ensuite merger à la branche master pour enfin l'envoyer sur github.
* Exceptionnellement, vous ne communiquerez entre co-équipier que par slack !

## Bower 

>les répertoires *bower_components* (là où bower range toutes librairies) et *nodes_modules*(là où node range toutes les librairies) ne doivent pas être pris en compte dans le versionning. Ils doivent être ignorés.
Pour ce faire, créer un fichier .gitignore puis ajouter les suivants : 
```
node_modules/
bower_components/
```

### Installer Bootstrap avec bower
Dans le terminal, allez dans le répertoire de votre projet et tapez la ligne suivante :
```
bower install bootstrap
```

### Installer Foundation avec bower
Dans le terminal, allez dans le répertoire de votre projet et tapez la ligne suivante :
```
git clone https://github.com/zurb/foundation-sites-template projectname
```
*(remplacer projectname par le nom du dossier de votre projet)*
```
cd projectname
npm install
bower install
```