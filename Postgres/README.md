# Dockerfiles
Repositório do Postgres e PgAdmin4

<hr>

Neste repositório contém o arquivo ".yml" do docker-compose.yml do Postgres e PgAdmin4:

<hr>

# Postgres

1. Nesta configuração contém o conteiner do postgres que roda na porta 5432 e do pgadmin4 que roda na porta 5050.

Primeiramente devemos baixar as imagens do postgres e do pgadmin4,
no terminal digite dentro da pasta que contém o arquivo docker-compose.yml:

> docker pull postgres

> docker pull dpage/pgadmin4

Para criar o container com os seus respectivos volumes  digite no terminal:

> docker-compose up

Quando for inicializar pela segunda vez e outras vezes digite no terminal dentro da pasta com o arquivo "docker-compose.yml":

> docker-compose start

Para parar o docker digite no terminal:

> docker-compose stop


