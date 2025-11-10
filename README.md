# Exposición Docker – Grupo 2

Este repositorio reúne los ejemplos usados en la exposición sobre Docker:

1. Instalación de Docker Engine y Docker Compose.
2. Registro e inicio de sesión en Docker Hub.
3. Dockerización de una aplicación Node.
4. Creación y uso de imágenes personalizadas.
5. Entorno multicontenedor con Docker Compose.
6. Nginx como proxy inverso para exponer servicios.

---

## Estructura del repositorio

- `Instalación/Comandos.txt`  
  Comandos para instalar Docker Engine, CLI y Docker Compose en Ubuntu.

- `Docker_Hub/Instalación_Pruebas.txt`  
  Pasos para iniciar sesión en Docker Hub, descargar imágenes y ejecutar contenedores de prueba.

- `Dockerizacion/Pasos.txt`  
  Uso del `Dockerfile` de la carpeta `Aplicacion/` para construir y ejecutar una imagen personalizada de Node, y cómo etiquetarla y subirla a Docker Hub.

- `Docker_Compose/Pasos.txt`  
  Ejemplo de uso de `docker compose` con un proyecto externo (frontend + backend) para mostrar un entorno multicontenedor.

- `Aplicacion/`  
  Aplicación Node.js sencilla que sirve archivos estáticos y expone un endpoint `/docker`.  
  Aquí se encuentra:
  - `Dockerfile`
  - `server.js`
  - `public/index.html`, etc.

- `Nginx_Proxy_Inverso/Pasos.txt`  
  Pasos para configurar Nginx como **proxy inverso** delante de la aplicación Node usando Docker Compose.
