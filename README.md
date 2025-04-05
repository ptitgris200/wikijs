# wikijs
## deploiement d'une stack wikijs deux branche principale une docker-compose une docker-swarm


sur ce dépot je vais vous fournir de quoi vous faire tourner votre propre wikijs dans un docker de votre choix. 

soit un simple docker et ça vous installera le tout dans un dossier ptitgris200/wikijs

soit sur un docker swarm ou vous devrez adapter les contraintes les exemples seront donné pour un serveur docker mono-node mais avec le swarm activé pour la gestion des stack. 
de telles conf sont aisément reportable sur une architecter avec des marster et des workers. 

## comment le depot ptitgris200/wikijs :
cloner le depot : 

```
git clone https://github.com/ptitgris200/wikijs.git

```

il y a deux Branches possibles a utiliser sans choix vous n'aurez que cette doc.

liste des branches à choisir :

docker-compose
docker-swarm

pour de ce faire utiliser la commande : 

```
# Basculer sur la branche docker-compose
git checkout docker-compose

# Basculer sur la branche docker-swarm
git checkout docker-swarm
```

///////////////////////////////////////////////////////////////////////////////
# wikijs
## Deployment of a Wiki.js stack with two main branches: one for docker-compose and one for docker-swarm

In this repository, I will provide you with everything you need to run your own Wiki.js in a Docker environment of your choice.

- Either a simple Docker setup, which will install everything in a folder named `ptitgris200/wikijs`.

- Or on a Docker Swarm, where you will need to adapt the constraints. The examples provided will be for a single-node Docker server but with Swarm enabled for stack management. Such configurations can easily be adapted to an architecture with masters and workers.

## How to use the repository ptitgris200/wikijs:
Clone the repository:


```
git clone https://github.com/ptitgris200/wikijs.git

```


There are two possible branches to use; without making a choice, you will only have this documentation.

List of branches to choose from:

- docker-compose
- docker-swarm

To switch to one of these branches, use the following commands:


```
# Switch to the docker-compose branch
git checkout docker-compose

# Switch to the docker-swarm branch
git checkout docker-swarm
```


enjoy using ptitgris200/wikijs !


















release note: 
06/04/2025-0 initialisation du projet
06/04/2025-1 traduction en anglais

