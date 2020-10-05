# INSTALLER SUBLIME TEXT 3

* * *

**Note:** Quand des raccourcis commençant par `CTRL` sont signalés, il convient de remplacer `CTRL` par `CMD ⌘` si on travaille sur Mac. 

* * *

## 1. Télécharger ST3
Rendez-vous sur le site de Sublime Text : [http://www.sublimetext.com](http://www.sublimetext.com). Au début octobre 2020, le numéro de la version la plus récente est *3211*. 

Le logiciel est disponible en version d’évaluation sans limite de temps. Si vous l’utilisez professionnellement, payer la modique licence est un must. Si vous ne payez la licence, une boite de dialogue vous interrompera très occasionnellement lors de vos sauvegardes pour vous rappeler de faire l’achat.

- Pour ⊞ Windows : cliquer sur le lien [Windows](https://download.sublimetext.com/Sublime%20Text%20Build%203211%20Setup.exe) => *Sublime Text Build 3211 Setup.exe*
- Pour  Mac : cliquer sur le lien [OS X](https://download.sublimetext.com/Sublime%20Text%20Build%203211.dmg) => *Sublime Text Build 3211.dmg*

## 2. Installer ST3
Exécuter le fichier .exe récupéré (double-cliquer dessus) ou ouvrez l’image .dmg et glissez l’icône de *Sublime Text* sur l’icône du dossier *Applications* 

# CONFIGURER SUBLIME TEXT 3

Une [documentation non officielle](https://docs.sublimetext.io) maintenue par la communauté et validée et hébergée par le créateur du logiciel, explique très en détail les customisations possibles.

*Sublime Text* est, comme beaucoup d’autres logiciels, une sorte de jeu de Légo™. On peut lui greffer de nombreuses extensions pour augmenter ses fonctionnalités et les adapater à nos besoins. Dans le vocabulaire de ST, ces extensions sont nommées *Packages*.

Une grand nombre d’opérations de ST sont réalisables via la palette de commande. La vidéo suivante vous la présente : http://youtu.be/YDRV6ZsGAfg

## 1. Installer des packages (procédure générale)

### 1.1. Voir la liste des packages disponibles

1. `CTRL`+`MAJ`+`P` pour avoir la liste des commandes disponibles
2. Taper *« list »* => choisir `Package Control: List Packages`
3. On voit apparaître la fenêtre de *Package Control* avec, dedans, la liste des packages installés

### 1.2. Installer un package

La procédure est la même pour tous les packages qu’on souhaite installer.
On utilise la commande `Package Control: install Package` de ST et on choisit dans la liste le package qu’on souhaite installer.

Procédure détaillée :

1. `CTRL`+`MAJ`+`P` pour avoir la liste des commandes disponibles 
2. Taper *« instal »* => choisir `Package Control: Install Package`
3. On voit apparaître la fenêtre de *Package Control* avec, dedans, la liste des packages non encore installés, qu’on peut donc installer
3. Taper un des mots constituant le nom du package qu’on veut installer => il le propose dans la liste => le choisir, il l’installe. Ça peut prendre quelques secondes. La barre de statut en bas de la fenêtre vous montre l’activité de téléchargement et d’installation en cours.

### 1.3. Quelques packages intéressants pour démarrer dans la création de pages Web

Les extensions potentiellement les plus utiles pour débuter sont :

- **Side Bar Enhancements**
	- [Screencast explicatif](https://youtu.be/ZVLXLGcaJ0Q)
	- Le menu latéral *(side bar)* liste les dossiers et fichiers contenus dans le dossier qu’on a ouvert ;
	- Sidebar Enhancements ajoute des options au menu de clic-droit dans l'arborescence des fichiers : permet, quand on choisit un fichier  dans la *side bar*, d’avoir un menu contextuel plus complet avec, notamment, l’option `open in browser`, qui permet d’ouvrir directement le fichier dans un navigateur sans devoir quitter ST. (N.B. On peut chosir le navigateur avec lequel ST va ouvrir le fichier en modifiant les préférences de ST, voir plus loin).
	- Installation : 
	  1. `CTRL`+`MAJ`+`P`
	  2. Taper *« instal »* => choisir `Package Control: Install Package`
	  3. Taper *« sidebar »* => choisir `SideBarEnhancements`
	- Utilisation :
	  - la *side bar* s’ouvre directement au démarrage de ST dès lors qu’on ouvre un dossier contenant plusieurs fichiers ;
	  - Sinon, dans le menu, choisir l’option `View` > `Side Bar`> `Show Side Bar`
- **Markdown Preview**
	- [Screencast explicatif](https://youtu.be/ENQaeewVSOc)
	- Permet d’afficher des fichiers balisés en markdown dans un navigateur (cette extension exporte le fichier markdown ouvert en HTML et l’ouvre directement dans le navigateur)
	- Installation :
	  1. `CTRL`+`MAJ`+`P`
	  2. Taper *« instal »* => choisir `Package Control: Install Package`
	  3. Taper *« markdown »* => choisir `Markdown Preview`
	- Utilisation :
	  1. Vous êtes dans ST avec un fichier .md ouvert
	  2. `CTRL`+`MAJ`+`P`
	  3. Taper *« markdown »* => choisir `Markdown Preview: Preview in Browser` puis `markdown`dans la 2e liste fournie
- **All Auto Complete**
	* [Screencast explicatif](https://youtu.be/GJEbbWmX43c)
	* Permet d’étendre l’auto-complétion au-delà des symboles qui sont présents dans le fichier courant.
	* Installation : 
		1. `CTRL`+`MAJ`+`P`
		2. Taper *« instal »* => choisir `Package Control: Install Package`
		3. Taper *« complete »* => choisir `All Auto Complete`
- **Emmet**
	* [Screencast explicatif](https://youtu.be/TEs2LE0fl10)
	* Permet d’utiliser des raccourcis et des alias, voir [Emmet Sheat Sheet](http://docs.emmet.io/cheat-sheet/))
	* Installation : 
		1. `CTRL`+`MAJ`+`P`
		2. Taper *« instal »* => choisir `Package Control: Install Package`
		3. Taper *« emmet »* => choisir `Emmet`
	* Utilisation :   
		1. Pour HTML :
			* Permet de taper rapidement des balises ou des blocs de balises HTML tout faits
			* *Comment ?* On tape des expressions raccourcies, ou une suite de balises séparées par des opérateurs (quantificateus, sélecteurs CSS, etc.) + `TAB`
				- Ex. a + `TAB`
				- Ex.	: html:5 + `TAB`, ou `!` + `TAB`
				- Ex. : ul>li*5 + `TAB` 
			* Voir [Emmet Sheat Sheet](http://docs.emmet.io/cheat-sheet/) pour les possibilités détaillées  
		2. Pour CSS :
			* Permet de taper une propriété CSS rapidement
			* *Comment ?* On tape le nom de la propriété raccourcie + `TAB`
			* Voir [Emmet Sheat Sheet](http://docs.emmet.io/cheat-sheet/) pour les possibilités détaillées
- **FindNonASCIICharacters**
	* Permet de trouver les caractères non-ASCII qui pourraient générer des erreurs dans le code
- **Autoprefixer**
	* Ajoute automatiquement les *préfixes de compatibilité* si nécéssaire en CSS
- **AdvancedNewFile** 
	* Ajoute quelques options au menu de clic-droit dans l'arborescence des fichiers
- **etc.**
		  
## 2. Changer les préférences générales de ST

​	[Screencast explicatif](https://youtu.be/R_g_ijJ5Bq4)

1. Récupérer les préférences par défaut de ST pour pouvoir les modifier :
	* Choisir dans le menu `Sublime Text`> `Preferences` > `Settings - Default`
	* Récupérer les préférences par défaut : tout sélectionner (`CTRL`+A), copier (`CTRL`+C)
	* On va coller ce contenu dans Settings - User
	
2. Enregistrer nos préférences dans le fichier des préférences de l’utilisateur :
	* Choisir dans le menu `Sublime Text`> `Preferences` > `Settings - User`
	* Initialiser (ou réinitialiser) si nécessaire les préférences de l’utilisateur en y insérant les préférences par défaut : on sélectionne tout (pour écraser) (`CTRL`+A), on colle les préférences par défaut récupérées à l’étape 1 (`CTRL`+V), on sauve (`CTRL`+S)
	* Opérer dans le fichier ainsi obtenu les modifications souhaitées, par exemple :
		- Changer la police : `CTRL`+F : font => "font_face": "consolas", (ou "courrier new")
		- Passage à la ligne : `CTRL`+F : wrap => "word_wrap": "true",
		- Convertir TAB en espaces : `CTRL`+F : translate => "translate_tabs_to_spaces": true
				
## 3. Changer les préférences d’un package installé

[Screencast explicatif](https://youtu.be/i8TkCDdYxtk)

Il s’agit de la même procédure que pour changer les préférences générales de ST, si ce n’est qu’on modifie cette fois le fichier *Settings - User* du package souhaité (par exemple *Side Bar*) qui se trouve dans *Package Settings*, et non plus le fichier *Settings - User*  de ST (qui se trouvait dans *Preferences*).

On utilise cette procédure pour, par exemple, changer le navigateur par défaut avec lequel ST va ouvrir notre fichier (quand on choisit `open in browser` dans la *Side Bar*).

En détail, cela donne dans ce cas :

1. Récupérer les préférences par défaut du package *Side Bar* pour pouvoir les modifier :
	* Choisir dans le menu `Sublime Text`> `Package Settings` > `Side Bar`> `Settings - Default`
	* Récupérer les préférences par défaut : tout sélectionner (`CTRL`+A), copier (`CTRL`+C)
	* On va coller ce contenu dans Settings - User
	
2. Enregistrer nos préférences dans le fichier des préférences de l’utilisateur :
	* Choisir dans le menu `Sublime Text`> `Package Settings` > `Side Bar`> `Settings - User`
	* Initialiser (ou réinitialiser) si nécessaire les préférences de l’utilisateur en y insérant les préférences par défaut : on sélectionne tout (pour écraser) (`CTRL`+A), on colle les préférences par défaut récupérées à l’étape 1 (`CTRL`+V), on sauve (`CTRL`+S)
	* Opérer dans le fichier ainsi obtenu les modifications souhaitées, par exemple :
		- Changer navigateur par défaut : `CTRL`+F : browser => "default_browser": "firefox"


## 4. Quelques raccourcis utiles

1. `CTRL`+ `S`
	
	* Enregistre le fichier
	
2. `CTRL`+ `F`
	
* Permet de rechercher une ou plusieurs occurrences d’un mot ou d’une expression
	
3. `CTRL`+ `A`
	
	* Sélectionne tout
	
4. Sélection puis `CTRL`+ `C`
	
	* Copie la sélection
	
5. Sélection puis `CTRL`+ `X`
	
	* Coupe la sélection
	
6. Curseur positionné à l’endoroit choisi puis `CTRL`+ `V`
	
* Colle la sélection précédememnt copiée
	
7. Sélection puis `CTRL`+ `D`
	* Permet de sélectionner les occurrences suivantes d’une sélection
	* Rend possible l’édition multiple
	
8. `CMD`+`CTRL`+`G`
    * Permet de sélectionner toutes les occurrences d’une sélection
    * Rend possible l’édition multiple

9. `ALT` + Souris : 
	
* Rend possible la sélection en colonne
	
10. `CTRL`+`SHIFT`+`W`
	
	* Permet d’encadrer une sélection avec une balise HTML
	
11. `CTRL`+`W`
    * Permet d’encadrer une sélection plus complexe avec plusieurs balises HTML en utilisant la syntaxe CSS
    * Exemple :
      - on tape
      
        ```
        pomme
        poire
        banane
        fraise
        ```
      - on sélectionne tout le texte, on tape `CTRL`+`W`  
        => ça encadre la sélection d’une balise `div`  
           et ça ouvre un panneau "Enter Wrap Abbreviation" qui attend le nom des balises qui devront encadrer les éléments de la sélection
      - on peut entrer une exepression du genre `ol>li*`  
        => ça génère le code suivant :
        
        ```
        <ul>
	        <li>pomme</li>
	        <li>poire</li>
	        <li>banane</li>
	        <li>fraise</li>
        </ul>
        ```
	
12. `CTRL`+`MAJ`+`P`
	* Donne la liste des commandes disponibles 
	* => quand on tape des mots de ce qu’on veut, il complète (logique floue)  
	et on a la liste de ce qui contient ces mots-là qui apparaît
	* => `ENTER` pour choisir la première proposition
	* => flèche pour se balader dans la liste et `ENTER`quand on est sur celle qu’on veut

	
## Ressources

* [Sublime Blog](https://www.sublimetext.com/blog/)
* [Sublime Text Mastery](https://laracasts.com/series/sublime-text-mastery)
* [Sublime Text Bookmarks](https://github.com/dreikanter/sublime-bookmarks)