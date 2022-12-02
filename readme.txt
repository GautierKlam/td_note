Nom : KLAM
Prénom : Gautier
Numéro étudiant : 31806683


Doc du TD noté

Pour lancer en local le build : 
Aller dans le fichier où il y a le Dockerfile, faire la commande ci dessous : 
 - [docker build -t index .]
L'image a été build, il faut la run. On peut le faire directement sur l'application Docker Desktop dans Images. On peut désormais run l'image index en précisant le port 80.
Aller sur un navigateur de recherche puis rentrer l'url [localhost:80], on peut voir notre application

Avec mogenius : 
Pour lancer l'application avec mogenius, j'ai suivu le tuto ci : https://docs.mogenius.com/getting-started/quickstart.
Tout d'abord j'ai créé un compte ensuite j'ai créé un nouveau cloudspace. Je lui ai donné un nom puis j'ai lié mon repository github pour qu'il fasse le lien entre mon compte mogenius et github.
J'ai également spécifié un port (80). Suite à cela, on m'a donné un "Internal Hostname et External Hostname" pour avoir accès à mon image en localhost ou sur le web.

Lien du mogenus :
td-note-prod-td-note-klam-o1wsx6.mo6.mogenius.io:80

Lien du git :
https://github.com/GautierKlam/td_note