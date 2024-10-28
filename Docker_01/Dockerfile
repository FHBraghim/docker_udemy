# Importar sistema operacional
FROM node:alpine

# Copiar tudo do diretório Docker para o diretório app (que será criado dentro da imagem)
COPY . /app

# Configurar diretório padrão para executar os comandos - Assim não é necessário passar o caminho em todo comando
WORKDIR /app

# Executar comando
CMD node app.js

# Essa imagem possuí o NodeJs, o Alpine e o App.
