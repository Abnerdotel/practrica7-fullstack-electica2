# Backend Dockerfile
FROM node:14

# Establece el directorio de trabajo
WORKDIR /app

# Copia solo package.json para instalar dependencias primero
COPY package.json /app/

# Instala las dependencias
RUN npm install

# Copia el resto del código
COPY . /app

# Expone el puerto del backend
EXPOSE 5000

# Comando para ejecutar la aplicación
CMD ["npm", "start"]

