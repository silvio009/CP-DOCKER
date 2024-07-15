# Define a imagem base
FROM node:lts-alpine3.19

# Define um usuário não privilegiado para executar a aplicação
USER node

# Define um diretório padrão para a aplicação
WORKDIR /app-money

ADD ./ .

# Exposição da porta para acesso à aplicação
EXPOSE 3030

# Define o comando padrão para iniciar a aplicação Node.js
CMD ["npm", "start"]
