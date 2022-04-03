# TP4_kubernetes

Ce TP consiste à utiliser la technologie "HELM Chart" afin d'automatiser le déploiement du projet.

Il consiste à :

- Déployer un serveur WEB
- Déployer un serveur de base de données avec MariaDB
- Créer un persistent volume ainsi qu'un persistent volume claim pour chacun des serveurs
- Créer un service permettant de pouvoir accéder au serveur web (avec NodePort pour mon cas)
- Ainsi qu'un service pour que le serveur web puisse accéder aux données de la BDD

Il est fait en sorte que dans le fichier Values.yaml, il est possible de modifier certaines valeurs de nos fichiers de configurations sans à avoir les modifier directement dans lesdits fichiers.

Pour terminer, un message s'affichera lors du déploiement du Helm chart afin d'expliquer comment accéder au serveur WEB.
