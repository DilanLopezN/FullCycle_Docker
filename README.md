# DESAFIO DOCKER FULL CYCLE
docker-node:
Desafio onde deveria criar uma imagem nodeJs, que utiliza um container do mysql para fazer insert no banco de dados
pós isso servir uma página mostrando o que foi inserido no banco atráves de proxy reverso na porta 8080 do nginx.

execultar: docker compose up -d 
acessar localhost:8080 no navegador

docker-go
Desafio de otimização de imagem multistagebuilding, onde teria que subir um hello word no docker hub com uma imagem com menos de 2mb
comando: docker pull dilanlopez/fullcycle:latest