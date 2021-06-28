###############################################################################################################################
###############################################################################################################################
###############################################################################################################################
###########################################                     ###############################################################
########################################### Guide d'utilisation ###############################################################
###########################################                     ###############################################################
###############################################################################################################################
###############################################################################################################################
###############################################################################################################################
1- Introduction : 
Il sagit d'un script permetant d'exploiter L'API abuseIPDB en plus d'un fichier journal projet.log pour decider de bloquer 
ou non des addresse IP qui peuvent metre en perile le serveur. 
2- Instalation :
Pour bien utiliser se script il faut disposer des commandes suivante :
- curl :envoyer des requetes en utilisant un protocol preciser    
- jq : permet de manipuler des fichier json pour recuperer des information celon une ou plusieure clefs
- sudo IPtables : Il faut donner la permission en tant que super utilisateur pour le blocages des addresses IP   
- mutt : Pour envoyer des email  
En plus dans le fichier message.txt vous pouvez configurer le corps du  message qui serra envoyer ladministarateur 
