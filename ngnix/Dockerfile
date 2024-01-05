# Usa la imagen base de Nginx
FROM nginx

# Establecer el directorio de trabajo
WORKDIR /usr/share/nginx/html

# Copia los archivos de la aplicación HTML al directorio de trabajo de Nginx
COPY index.html .
COPY assets/Cerati_G.jpg .

# Exponer el puerto 80 para que Nginx pueda servir la aplicación
EXPOSE 80

# El comando para iniciar Nginx cuando se ejecute el contenedor
CMD ["nginx", "-g", "daemon off;"]
