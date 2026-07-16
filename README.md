# test_github_actions_2_h_1

Este repositorio contiene una página web estática sencilla de ejemplo, diseñada para demostrar el uso de GitHub Actions con despliegue automático en GitHub Pages.

## ¿Qué hace este proyecto?

El proyecto muestra una página básica en HTML con el mensaje "Hello, world!😎". Su propósito principal es servir como ejemplo mínimo de un sitio estático que puede publicarse automáticamente cuando se actualiza la rama principal.

## Estructura del repositorio

- [index.html](index.html): archivo principal con el contenido de la página.
- [.github/workflows/deploy.yml](.github/workflows/deploy.yml): flujo de trabajo que publica el sitio en GitHub Pages.

## Despliegue automático

Cada vez que se realiza un push a la rama main, GitHub Actions ejecuta el workflow de despliegue y publica el contenido del repositorio en GitHub Pages.

## Cómo visualizarlo

Puedes abrir el archivo [index.html](index.html) directamente en tu navegador o acceder a la URL pública generada por GitHub Pages una vez que el despliegue esté activo.

## Tecnologías utilizadas

- HTML
- GitHub Pages
- GitHub Actions