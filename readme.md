# Docker + PHP + Nginx + Mysql + Postgres + Redis
Está imagem foi desenvolvida afim de facilitar a vida do desenvolvedor PHP, permitindo assim que de forma fácil um dev consiga executar todo o ambiente de desenvolvimento PHP. 

# Imagem Docker PHP com Nginx
[Ver imagem no Docker Hub](https://hub.docker.com/r/urnau/php-community)

## Requisitos
- Ter o Docker instalando em sua máquina. Este passo a passo funciona tanto para ambiente Linux como para Windows e macOS.
- Caso você deseje subir uma imagem customizada para seu próprio Docker Hub é necessário então ter uma conta no [Docker Hub](https://hub.docker.com).


## Atenção
- Não execute os comandos de docker-compose build se este repositório estiver dentro de um subsistema Linux, como o WSL.

- Caso o comando `sh` não sirva para você executar os scripts, então experimente utilizar `./script-...`.


## Outras informações
- Caso precise remover as configuções de sites do Nginx, acesse a pasta docker/nginx/sites e lá encontre e remova as configurações `.conf` que desejar.

- Caso precise derrubar um container
> sh script-drop-container.sh


- Caso precise visualizar quais containers estão em execução
> sh script-docker-running.sh


- Caso precise entrar em um container
> sh script-access-container.sh