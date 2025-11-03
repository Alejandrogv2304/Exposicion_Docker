# Imagen base ligera de Node.js
FROM node:18-alpine

# Directorio de trabajo dentro del contenedor
WORKDIR /usr/src/app

# Copiar archivos de configuración
COPY package*.json ./

# Instalar dependencias
RUN npm install --production

# Copiar el resto del código
COPY . .

# Exponer el puerto de la app
EXPOSE 3000

# Comando para ejecutar la app
CMD ["node", "server.js"]
