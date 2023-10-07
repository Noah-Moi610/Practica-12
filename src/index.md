---
layout: layout-base.njk
title: Bienvenido a mi Blog
---

# {{ title }}

## Articulos de Blog

### Categoría libros

{% for libro in collections.libros %}

- [{{libro.data.title}}]({{ libro.url }})

{% endfor %}

### Categoría películas

{% for pelicula in collections.peliculas %}

- [{{pelicula.data.title}}]({{ pelicula.url }})

{% endfor %}

## Encabezado 2

![Flujo de Git](https://jonmircha.com/img/blog/git-flow.png)

Tecnologías que hemos aprendido:

- Git
- GitHub
- Markdown
- Terminal
- VS Code
