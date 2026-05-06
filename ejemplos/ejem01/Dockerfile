# 1. Usamos la versión que permite conectar VS Code 
FROM php:8.2-apache

# 2. Automatizamos la instalación de Vim (para que no se borre al relanzar)
RUN apt-get update && apt-get install -y vim

# 3. Copiamos tus archivos locales al contenedor
COPY src/ /var/www/html

# 4. Información extra
EXPOSE 80
LABEL maintainer="Sol De Francesco"