﻿# demohello-worldphp
Run Following

1)  docker build -t my-php-app .
    docker tag my-php-app:latest pareshrane/my-php-app
    
    docker image push pareshrane/my-php-app:latest    



2)  docker context use default
    minikube start

3) kubectl apply -f php-app-deployment.yaml

4) kubectl apply -f php-app-service.yaml

5) minikube service my-php-app-service --url
