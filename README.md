# PARCIALII_4090191026

Este es un ejemplo de un sitio web simple desplegado en contenedores Docker, utilizando el servidor web Apache y HTML.

## Tecnologías Utilizadas

- [Docker](https://www.docker.com/): Plataforma de contenedores que facilita la creación, despliegue y ejecución de aplicaciones en contenedores.

- [Apache HTTP Server](https://httpd.apache.org/): Servidor web de código abierto ampliamente utilizado.

- HTML (HyperText Markup Language): Lenguaje de marcado estándar para la creación de páginas web.

## Instrucciones de Uso

1. Asegúrate de tener Docker instalado en tu sistema.

2. Clona este repositorio:

   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git

   
1. Navega al directorio del proyecto:
    cd tu-proyecto

2. Construye la imagen de Docker
    docker build -t nombre-imagen .
3. Ejecuta el contenedor:
    docker run -d -p 80:80 nombre-imagen
4. Abre tu navegador web y ve a http://localhost para ver el sitio web.

# Estructura del Proyecto
Dockerfile: Archivo de configuración para construir la imagen de Docker.

index.html: Archivo HTML que contiene el contenido del sitio web.

# Contribuir
Si deseas contribuir, siéntete libre de abrir un pull request.
