figuration de gitlab_ci: 
	* definir un password par exemple xyz qui serra un password root
	* puis se connecté user : root et password: xyx
2- Crée un utilisateur: settings > admin area > new user
   pour avoir un server sntp pour l'envoi de mail il faut edité le compte: edit > password: xxxx et save puis deconnecté vous et reconnecté vous avec user crée
3- Crée un repository
4- Configuré le runners:
   Pour configuré le runners il faut utilisé le le password root
   admin area > runners: (cherché le runners puis) > edit: coché Run untagged job
5- Pour posté l'image on doient definir des variables d'environnement
	CI/CD > setting > CI/CD > variable (definir vos variables)
6- Le badget
   CI/CD > setting > CI/CD > Generale pipline > Markdown: copie le lien puis coller dans le READMIE
7- Facultatif
   crée une nouvelle branche et push sur le nouveau branche
8- Faire le merge request(gitlab) pull request(github) pour lié des branche (master et bagde)
   cliqué sur badge > create merge request > assignée
   

REMARRQUE
Crée un nouveau branche: git branch NomBranche
Deplacer entre les branches: git checkout -b NomBranche
Voir le status: git statun

