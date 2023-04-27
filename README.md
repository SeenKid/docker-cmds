# docker-cmds

## Image : Image du conteneur
-	docker image ls
-	docker build
-	docker rm / image rm


## Instance : le conteneur
-	docker ps (-a)
-	docker run (-d (mettre en arrière-plan) –name (donner un nom) -v(volume) -e(variable d’env))
-	docker rm -f 
-	docker start & stop & restart
-	docker exec (-it) <machine> (commande)


## Volume : là ou sont stockées les données 
-	docker volume ls
-	docker volume create
-	docker volume rm
-	docker volume prune


## Network : 
-	docker network ls
-	docker network create
-	docker network rm
Docker = commande de base

Docker exec : mettre -it si on veut interagir avec l’outil

