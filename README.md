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

#### On exécute :
    export CONFLUENT=7.5.1
    export CONFLUENT_DOCKER_TAG=7.5.1
    export CONFLUENT_SHORT=7.5
    export CONFLUENT_PREVIOUS="7.5.0"
    export CONFLUENT_RELEASE_TAG_OR_BRANCH=7.5.1-post
    export CONFLUENT_MAJOR=7
    export CONFLUENT_MINOR=5
    export CONFLUENT_PATCH=1
    export CP_VERSION_FULL="$CONFLUENT_MAJOR.$CONFLUENT_MINOR.$CONFLUENT_PATCH"

### Pour lancer notre exemple :

    docker compose up -d 
    
## Pour voir les conteneurs lancés :

    docker ps -a

## Pour arrêter l'instance lancée : 

    docker compose down

# Fin du TP
