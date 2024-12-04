# Web de Make Classic Games

[![ci](https://github.com/makeclassicgames/makeclassicgames.github.io/actions/workflows/ci.yml/badge.svg)](https://github.com/makeclassicgames/makeclassicgames.github.io/actions/workflows/ci.yml)

Web creada con MKDocs y el tema Bootstra386; donde se pondrá información y ejemplos sobre el canal. Puedes encontrar la web en: https://makeclassicgames.dev.

## Despliegue en local

Para desplegar en local, necesitaras tener instalado ```python``` y el gestor de paquestes ```pip```. Una vez instalados dichas herramientas, se requeriran los paquetes ```mkdocs mkdocs-bootstrap386```:

```bash
pip install mkdocs mkdocs-bootstrap386
```

Una vez instalados podemos desplegar la web con el siguient comando:

```bash
mkdocs serve
```

Esto desplegará un servidor web con la generación automática del sitio estático en la dirección:

http://localhost:8000
