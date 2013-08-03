## Wifi Shakirail

L'infrastructure est documentee sur le wiki du Loop :

http://wiki.leloop.org/index.php/Shakirail

### [list_uplink]

Affiche la liste des reseaux, triee par qualite de reception.

### [check_uplink]

Ce script verifie que la connexion est toujours etablie.

Le cas echeant, il cherche a se reconnecter, en utilisant parmi les reseaux configures celui qui a la meilleure qualite de reception.

### [root.crontab]

Fait tourner `[check_uplink]` toutes les 5 minutes.
