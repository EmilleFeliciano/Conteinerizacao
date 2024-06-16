#Usando uma imagem oficial MySQL
FROM mysql:latest

# Definindo variáveis de ambiente do MySQL
ENV MYSQL_ROOT_PASSWORD=root_password
ENV MYSQL_DATABASE=BANCO_DADOS_IT_TALENT

# Copiando o arquivo SQL para o diretório Docker
COPY dump.sql /docker-entrypoint-initdb.d/

#Porta MySQL
EXPOSE 3306

