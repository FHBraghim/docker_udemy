# Importar sistema operacional
FROM node:alpine

# Copiar tudo do diretório Docker para o diretório app (que será criado dentro da imagem)
COPY . /app

# Configurar diretório padrão para executar os comandos - Assim não é necessário passar o caminho em todo comando
WORKDIR /app

# Executar comando
CMD node app.js

# Essa imagem possuí o NodeJs, o Alpine e o App.

# Docker

# docker ps -a = lista os containers "pausados"

# Container vs VM
#     A VM vai utilizar todo o hardware para o processamento para sistemas diferentes, seria necessário uma VM para cada OS.
#     Já com o Docker apenas um sistema é utilizado, onde são criados os containers, cada um com o seu OS. Esses containers rodam de forma isolada.
#     Com containers a inicialização da aplicação é muito mais rápida do que em VMs.

# systemctl --user start docker-desktop (comando para iniciar o docker desktop)
# systemctl --user stop docker-desktop (comando para encerrar)
#       SOLUÇÃO PARA BURLAR QUANDO DESKTOP NÃO INICIAR
#            $ sudo sysctl -w kernel.apparmor_restrict_unprivileged_userns=0
#            $ systemctl --user restart docker-desktop
#
#
#
#


# docker file - É o responsável por transformar a aplicação em uma imagem docker
#     Imagem:
#         Pedaço do OS
#         Ambiente (node por exemplo)
#         Arquivos
#         Bibliotecas
#         Variaveis

#     Container:
#         É um processo. Armazena a imagem.
#         (É o container que é "enviado" para o servidor - Transferencia de ambiente de desenvolvimento para ambiente de teste/produção)

# Docker Hub (registry):
#     Como GitHub, só que para docker, é um repositório de containers

# Dockerfile:
#     O arquivo deve ser criado com D maiúsculo e o restante minúsculo, não possuí extensão
#     A primeira linha deve conter o OS que será utilizado

# Comandos:
#     docker build -t welcome-to-docker .
#     Constroi a imagem e -t atribui um nome a imagem (nesse caso o nome é welcome-to-docker)


############ Linux

# it - sistema interativo
# é possível rodar uma imagem sem precisar baixa-la usando o -it

#   docker run -it ubuntu

# whoami
# echo = print
# echo $0 = mostra a pasta que estou
# history = enumera e mostra os comandos utilizados recentemente
# apt = advanced package tool
#       apt list = lista todos os pacotes instalados
#       apt update
#       apt install
#       apt remove nome_do_pacote
#
#
#   Sistema de arquivos Linux
#       Root = /
#          dir = bin, dev, etc

# bin(binários), dev(arquivos device), etc(extended tool text configuration - arquivos config de host)
# Google = Linux Directory Structure