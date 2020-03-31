# Dockerfiles
Repositório de docker-compose.yml
<hr>

Neste repositório contém os arquivos docker-compose.yml para subir os respectivos containers:

# Laradock

1 nginx - as configurações são inseridas na pasta nginx/sites/file.conf, o arquivo file.conf pode variar o nome acordo como foi criado mas sempre deve ter a extensão ".conf" no final;
2 phpmyadmin - roda na porta 80;

<hr>

# Mysql - Workbench

1 Workbench - para acessar a parte gráfica entre dentro do container com o seguinte comando no terminal:
> docker-composer exec mysql-workbench

<hr>

# Postgres

1 Nesta configuração contém o conteiner do postgres que roda na porta 5432 e do pgadmin4 que roda na porta 5050.

Primeiramente devemos baixar as imagens do postgres e do pgadmin4,
no terminal digite dentro da pasta que contém o arquivo docker-compose.yml:

> docker pull postgres

> docker pull dpage/pgadmin4

Para criar o container com os seus respectivos volumes  digite no terminal:

> docker-compose up

Quando for inicializar pela segunda vez e outras vezes digite no terminal dentro da pasta do arquivo "docker-compose.yml":

> docker-compose start

** Para parar o docker digite no terminal:

> docker-compose stop

