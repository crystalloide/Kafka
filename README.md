# Kafka : installation, lancement, puis utilisation dans gitpod

## Rappel : nous sommes ici : https://github.com/crystalloide/Kafka

## Pour ouvrir un environnement Gitpod en ligne avec un simple navigateur web : 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/crystalloide/Kafka)

## Pour vérifier - si nécessaire - si des workspaces sont déjà utilisés dans Gitpod :

## https://gitpod.io/workspaces

# 1ère façon d'utiliser Kafka : via docker : 

### Pour récupérer la dernière version de l'image mongoDB disponible dans Docker Hub : 

####  https://hub.docker.com/search?q=confluentinc%2Fcp-kafka

#### https://github.com/confluentinc/cp-demo

    docker pull confluentinc/cp-kafka:latest

### Pour lancer notre exemple : Attention, ici il faut lancer  : 

    bash /workspace/Kafka/scripts/start.sh 
    
###  Au lieu de la commande habituelle : 

    docker compose up -d 
    
## Pour voir les conteneurs lancés :

    docker ps -a

## Pour arrêter l'instance lancée : 

    docker compose down

# Fin du TP
