# SSH_connexion

Je vais présenter différente connections en SSH. Toutes ces connections se feront en Administrateur.


## Depuis Windows vers Debian
Dans cette configuration le serveur sera la machine Debian, et le client sera la machine Windows.  
`PermitRootLogin yes` : Pour se connecter sur Debian en "root", il faut autoriser la connection dans le fichier de configuration (dans `/etc/ssh/ssgd_config`) et décommenter la ligne ``#PermitRootLogin`` et ajouter yes.  
`systemctl restart sshd.service` : Il est nécessaire de redémarrer le serveur ssh sur debian.  
`systemctl status sshd.service` : Pour vérifier l'état du status.  



## Depuis Windows vers Windows
