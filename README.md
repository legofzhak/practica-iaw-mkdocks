# Práctica: Creación de un sitio web estático con MkDocs y GitHub Pages
---
MkDocs es un generador de sitios web estáticos que nos permite crear de forma sencilla un sitio web para documentar un proyecto. El contenido del sitio web está escrito en texto plano en formato Markdown y se configura con un único archivo de configuración en formato YAML.

## Creación de un contenedor Docker con MkDocs y el theme Material
---
Crear un nuevo proyecto (Comando: new)
En primer lugar vamos a situarnos en el directorio donde queremos crear nuestro proyecto. En nuestro caso será el directorio proyecto.

Para crear la estructura de archivos del proyecto MkDocs podemos hacer uso del comando new, como se muestra en el siguiente ejemplo.

```
docker run --rm -it -p 8000:8000 -v "$PWD":/docs squidfunk/mkdocs-material new .
```

## Archivo de configuración mkdocs.yml

Dentro del directorio de nuestro proyecto deberemos crear el archivo de configuración YAML mkdocs.yml.

```YML

```