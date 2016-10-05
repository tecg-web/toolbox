#Quelques définitions pour bien démarrer
##Extension d’un nom de fichier
Il existe différents types de fichiers informatiques. Tous ne sont qu’un ensemble de « 1 » et de « 0 », mais c’est le type du fichier qui permet de décider comment interpréter ces « 1 » et ces « 0 ». 

Ainsi un fichier identique (les mêmes « 1 » et les mêmes « 0 ») de type « mp3 » ne veut pas dire la même chose que son homologue de type « word » ou « bitmap ». 

C’est dans l’extension du fichier que se trouve l’information du type du fichier. L’extension d’un nom de fichier prend la forme d’un code de 3 ou 4 lettres derrière le nom du ficher et séparée de ce nom par un « . ».

Par défaut l’option cochée « `Outils` > `Option des dossiers` > `Affichage` > `Masquer les extensions des fichiers dont le type est connu` » de l’explorateur Windows nous empêche de voir apparaître les extensions des fichiers.

Pour ce qui nous concerne, nous utiliserons surtout les extensions suivantes :

- **.html** pour les documents html (fichiers qui contiennent du code html) ;
- **.css** pour les feuilles de style (fichiers sui contiennent du code css) ;
- **.js** pour les fichiers javascript ;
- **.md** pour les fichiers markdown.

##Editeur de texte
Un éditeur de texte est un logiciel, tel que *Sublime Text*, *Atom*, *Notepad++*, *Smultron*, *VIM* , ... (il en existe bien d'autres), destiné à la création et l’édition de fichiers textes. Il est capable d’écrire le texte que nous tapons dans un fichier informatique.
 
Un éditeur de texte se distingue d’un traitement de texte par le fait qu’il est orienté lignes de code plutôt que paragraphes, et que les fichiers textes ne contiennent pas de mise en forme (taille et genre de la police, etc.). Le traitement de texte a un format de fichiers élaboré, contenant les informations de présentation.

L’éditeur utilise des fichiers de texte purs, présentés avec une police monospace à chasse fixe. Cette police permet d'aligner verticalement le texte, ce qui est utile avec certains types de fichiers tabulés (code source, etc.). 

##Coloration syntaxique
Le texte que nous écrivons dans un fichier au moyen de l’éditeur respectera toujours une syntaxe spécifique (soit html, soit css, soit js).

Les éléments de syntaxe différents seront coloriés dans différentes couleurs. C’est ce qu’on appelle la coloration syntaxique (c’est l’équivalent de « souligner les verbes en rouge, les sujets en verts, etc. »).


##Indentation
Le texte, qu’il soit en HTML, XHTML, XML, CSS ou javascript, que nous écrivons dans un éditeur sera indenté, c'est-à-dire qu’il respectera des conventions d’alignement qui seront vues pendant l’année.

##Markdown
Markdown est un langage de balisage léger créé par John Gruber et Aaron Swartz en 2004. Son but est d'offrir une syntaxe facile à lire et à écrire.

Un document formaté en Markdown devrait pouvoir être publié comme tel, en texte, sans donner l’impression qu’il a été marqué par des balises ou des instructions de formatage.

Nous publierons vos énoncés d’exercices en markdown et vous pourrez les lire directement dans un navigateur grâce à l'extension « Markdown Preview: Preview in Browser » de Sublime Text.

##Navigateur
Un navigateur Web est un logiciel conçu pour consulter le World Wide Web. Il est capable de lire (à partir du disque ou du réseau) et d’interpréter du texte qui respecte l’une de ces syntaxes : xml, xhtml, html, css et javascript. Sur base des textes reçus, le navigateur affiche la page Web mise en forme et exécute les scripts reçus.

Techniquement, un navigateur est au minimum un client HTTP.

La fonction principale d’un navigateur Web est donc de permettre la consultation d’informations disponibles (« ressources » dans la terminologie du Web) sur le World Wide Web. Les principales étapes de la consultation d’une ressource sont les suivantes :

1. L’utilisateur donne au navigateur Web l’adresse Web de la ressource à consulter. Il existe trois manières de donner une adresse Web :
	- taper soi-même l’adresse Web dans la barre d'adresse du navigateur ;
	- choisir une ressource dans la liste des favoris (ou marque-pages ou bookmarks), sachant qu’à chaque favori est associée une adresse Web ;
	- suivre un hyperlien, sachant qu’à chaque hyperlien est associée une adresse Web ;
2. Le navigateur se connecte au serveur Web hébergeant la ressource visée et la télécharge. Le protocole de communication généralement utilisé est HTTP ;

3. le moteur de rendu du navigateur traite cette ressource, télécharge les éventuelles ressources associées et affiche le résultat sur l'écran de l'utilisateur.

Le navigateur Web est constitué

- de composants permettant de communiquer suivant des standards des réseaux ;
- d’un moteur de rendu des standards du Web ;
- d’une interface utilisateur adaptée au système d’exploitation qui l'accueille et, accessoirement,
- d’un gestionnaire d'extensions appelées plugins.

Il existe de nombreux navigateurs Web, pour toutes sortes de matériels (ordinateur personnel, tablette tactile, téléphones mobiles, etc.) et pour différents systèmes d'exploitation (*GNU–Linux*, *Windows*, *Mac OS*, *iOS* et *Android*). Les plus utilisés à l'heure actuelle sont, *Google Chrome*, *Mozilla Firefox*, *Internet Explorer*, *Safari* et *Opera*.

##Serveur Web
On appelle serveur Web aussi bien le matériel informatique que le logiciel qui joue le rôle de serveur informatique sur un réseau local ou sur le World Wide Web.

En tant que matériel, un serveur Web est un ordinateur comme un autre. Comme tout serveur, il est relié à un réseau informatique et fait fonctionner un logiciel serveur.

En tant que logiciel, un serveur Web est plus précisément un serveur HTTP, HTTP étant le principal protocole de communication employé par le World Wide Web.

Le plus souvent, un serveur Web fait fonctionner plusieurs logiciels ensemble. On retrouve la combinaison *Apache* (serveur HTTP), *MySQL* (serveur de base de données) et *PHP*, qui peuvent être différents selon le système d’exploitation :

- Sous Linux, cette combinaison s’appelle *LAMP* (sigle de « *Linux*, *Apache*, *MySQL*, *PHP* ») ;
- sous Windows, *WAMP* (« *Windows*, *Apache*, *MySQL*, *PHP* ») ;
- sous Mac, *MAMP* (« *Macintosh*, *Apache*, *MySQL*, *PHP* »).

D’autres distributions sont disponibles pour le public comme *Nginx* (prononcez « engine x ») ou encore *lighttpd* (lighty).

Il existe aussi la distribution de Microsoft nommée *IIS* (prononcez « 2 i s ») pour Internet Information Services.

Le serveur HTTP (comme *Apache*, par exemple) est capable de recevoir (d’Internet) des demandes de page web (dites « requêtes http ») et d’envoyer vers le demandeur la page web souhaitée (dans une « réponse http »).

##Script côté client
C’est un script, tel qu’un script écrit en javascript, destiné à être exécuté par le navigateur sur la machine de l’internaute. La plupart du temps, le but de ce script sera de modifier le contenu ou la mise en forme de la page Web en fonction des actions de l’internaute (clic sur un bouton, etc.).

##Script côté serveur
C’est un script, tel qu’un script écrit en php, destiné à être exécuté par le serveur Web, avant que celui-ci n’envoie la page Web à l’internaute. La plupart du temps, le but de ce script sera de construire une page Web « sur mesure » (en fonction par exemple des données se trouvant dans une base de données) avant de l’envoyer.
