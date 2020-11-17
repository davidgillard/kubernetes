# kubernetes

playbook permettant de déployé un cluster kubernetes sur centos 8

Prérequis pour le Master et les Noeuds

1. Déployez trois serveurs cloud en CentOS 8 . Un pour le maître et deux autres pour le nœud worker.

cette étape est réalisé à l'aide de l'outil Vagrant d'Harchicorp (Vagrantfile)
pour le lancement du Vagranfile 
se positionner dans creation_cluster > Plusieurs_serveurs :
lancer la commande "vagrant up"

2. Utiliser le playbook créer à cette effet pour déployé le cluster sur les trois VM vagrant
