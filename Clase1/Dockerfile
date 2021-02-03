# Basar el contenedor en la última imagen de ubuntu
FROM ubuntu:latest

# Autor del Dockerfile
LABEL maintainer="nicosoria18@gmail.com"

# Actualizar paquetes a la última versión
RUN apt-get update && apt-get upgrade -y

# Instalar aplicativos necesarios
RUN apt-get install git -y
RUN apt-get install python3 python3-pip -y