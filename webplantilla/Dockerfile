# Imagen base con Nginx
FROM nginx:alpine

# Borramos los archivos por defecto de Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copiamos todo tu proyecto (index.html, assets, etc.) al directorio web de Nginx
COPY . /usr/share/nginx/html/

# Exponemos el puerto 80 (interno del contenedor)
EXPOSE 80

# Nginx arranca solo con la imagen base, no hace falta CMD
