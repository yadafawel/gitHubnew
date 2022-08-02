## *GitHub*
## 1 Présentation
### 1.1 GitHub

*Plateforme collaborative* pour dev, plus grand espace de stokage de travaux collaborative dans le monde ! GitHub en lui-même n'est plus q'un reseau sociale comme FB. Vous construisez un profil, vous y depposez des projet à partager et vous connectez avec d'autre utilisateur en suivant leur compte. Même si le oluoart des utilisateur y deposent les projets de programmes ou de  code , riens ne vous empeche d'y placer de textes ou tout type de fichier à presenter dans votre repestoire de projets. 

### 1.2 Git 
Git est un *logiciel de controle de version*, ce qui signifie quil, gere les modification d'un projet sans écraser n'importe quelle partie du projet.

## 2 Git  et GitHub 
## 2.1 Vocabulaire 
**ligne de commande** : En gros : le programe de l'ordinateur que nous utilisons pour entrez des commandes Git , Dans le monde UNIX, on dit que'on travaille en "ligne de commande" pour désigner le fait d'interagir avec un sytème informatique  en entrant des lignes d'instractions textuelle dans un terminal, et non  à l'aide d'une interface graphique.
les commands tapé dans le términal sont interp)rette pars un shell.


journal du Net <https://www.journaldunet.fr/web-tech/dictionnaire-du-webmastering/1445276-commande-informatique-definition-precise-et-exmples/>  


**Depos**: Un repertoire ou de l'espace de stokage ou vos projets peuvent vivre; les utilisateur de GitHub racourcissent en "repo" por "repository". il peut etre un space de stokage sur GitHub ou sur un autre heberger en ligne. à l'interieur d'un depot, vous pouvez conserver des fichiers des coder, des fichier des text des images.


**Control de version**: Fondamentalement, l'objective pour lequel GitHub a été conu. Quand vous avez fichier word , vous l'ecriviez à chaque fois que vous sauve garder plusieur versions. Avec git vous n'est plus  obliger de faire ça. Git conserve des "instance" de chaque point dans l'historique d'unproject,de sort que vous ne pouvez jamais le perdre ou l'ecraser.

**Commit** :  c'est la command qui donne à git toute puissance. Quand vousb commettez, vous prenez un intentané, une photo de votre depot à ce stade vous dennant poin de controle que vous pouvez  ensuit réevaluez ou tout simplement restorez votre project à cette version. il est nécessaire de rapeler que le nom dde vos commit doivent_être parlant afin de savoire à quel stade de projet celui-ci a été fait 

**Branche** : Comment   plusieur personne travaille sur un projet en même temps sans que git ne s'enbrouille?  Habituellement, elle se débranchent  de projet principale avec leur propre version completès, des modification que'elles on chaque'un produites de leur côté.
Apres avoir términé, il est temps de fusionner cette branche pour la ramener ver la branche master, le repertoire principale de projet ;

## 2.2 Commande specifique de git
**Git init**:  Initialiser un nouveau depot git jusqu'a ce que vous executer les commande Git qui suivant.

**git config** : Racourci de configuration, ceci est tout particulièrement utile quand vous paramètrez Git pour la premiere fois indentifiant et mot d'utilisateur.

**git help** : oublie une commande? ppour afficher les 21 commande de git;


**git status** : Verifier le status de votre rpo. Voir les fichiers et quelle sont les modifications à commiotter et sur quelle branche ou repos vous êtes entrain de travailler.

**git add**: Ceci n'ajoute pas des fichiers dans votre repo, au lieun de cela porte de nouveaux fichiers à l'attention de git . Apres avoir ajoute des fichiers ils dont inclus dans les instentanes du depos Git.


**git commit** : La commande la plus importente de Git. Apres avoir effactuer toute sorte de modification vous entrez ça affin de prendre  un instantanes de depos. le metre en memoire. en ecris ça sous la forme de git commit  -m ' voutre message ' . Le -m indique que la section suivante  de la commande devrait etrelu comme in message

**git branche** : vous travaillez avec plusieurs collaborateurs et vous voulez produire des modification de voutre cote? cette commande vous permet de construir u,e  nouvvelle branche, ou une chronologie de commits, des modifications et des ajouts de fichier qui sont copletement les votres. votre titre va apres la commende . si vous vouler creer une nouvelle branche appeller 'yadaf' vous saisireez git branche Yadaf.


**git checkout** : c'et=st une commande de navigation quivous permet de vous deplaacer ver le reportoire que vous voulez verifier . voous pouvez utiliseer cette commande sous la forme de git checkout master pour regarder la branche master, ou get checkout yadaf pour regardder un autre branche.


**git merge**: lorsque vous avez finis de travailler sur un branche vous pouvez fusionneer vos modifications vers la branche master , qui est visible pour tous les collaborateur. git merge yadaf prendrait toutes les modification que vous avez apporteer à la branche yadaf  et les ajoutera à la branche master.


**git push** : si vous travaille sur votre ordinateur en local et vous voulez la version le plus a hjour  de votre repo pour travailler dessus , vous pullez les modifications provenant de GitHub avec cette commande.

**git clone** : Permet de dupliquer , cloner un existantr sur GitHub pour l'avoir en local. La commande git clone doit être suivit deb url de repo correspondent qui copie depuis GitHub direct.