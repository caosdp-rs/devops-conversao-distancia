# conversao-distancia

Criando a imagem do container

docker build -t conversao-distancia -f Dockerfile .


Executando o container
docker container run -d -p 8081:5000 conversao-distancia

Listando os containers
docker container ls

Listando os containers parados  
docker container ls -a

Parando o container
docker container stop <container_id>

Removendo o container
docker container rm <container_id>
Removendo a imagem
docker image rm conversao-distancia



