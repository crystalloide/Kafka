# Kafka : installation, lancement, puis utilisation dans gitpod

## Rappel : nous sommes ici : https://github.com/crystalloide/Kafka

## Pour ouvrir un environnement Gitpod en ligne avec un simple navigateur web : 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/crystalloide/Kafka)

## Pour vérifier - si nécessaire - si des workspaces sont déjà utilisés dans Gitpod :

## https://gitpod.io/workspaces

# 1ère façon d'utiliser Kafka : via docker : 

### Pour récupérer la dernière version de l'image mongoDB disponible dans Docker Hub : 

#### [ https://hub.docker.com/search?q=confluentinc%2Fcp-kafka](https://hub.docker.com/r/confluentinc/cp-kafka)
#### [ https://hub.docker.com/search?q=confluentinc](https://hub.docker.com/r/confluentinc/cp-kafka)
#### [ https://github.com/confluentinc/cp-demo](https://github.com/confluentinc/cp-demo)


    docker pull confluentinc/cp-kafka:latest


    sudo chmod 777 -Rf /workspace/Kafka/

### Pour lancer notre exemple : Attention, ici il faut lancer  : 

    bash /workspace/Kafka/scripts/start.sh 
    
###  Au lieu de la commande habituelle : 

    docker compose up -d 
    
## Pour voir les conteneurs lancés :

    docker ps -a


## Pour profiter de l'envrionnement instancié, avec un navigateur web (adapter l'URL selon votre cas) : 

https://9021-crystalloide-kafka-zlukglrcx42.ws-eu108.gitpod.io/login

Login :

    superUser

Mot de passe :

    superUser
    

## Pour arrêter l'instance lancée : 

### Pour lancer notre exemple : Attention, ici il faut lancer  : 

    bash /workspace/Kafka/scripts/stop.sh 
    
###  Au lieu de la commande habituelle : 

    docker compose down

# Fin du TP
