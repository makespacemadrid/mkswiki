# Mkdocs
- Documentación completa [mkdocs.org](https://www.mkdocs.org).
- Documentación del theme [material](https://squidfunk.github.io/mkdocs-material/reference/)
- [Catálogo de plugins](https://github.com/mkdocs/catalog?tab=readme-ov-file#-links--references)

## Dependencias
```
pip install mkdocs mkdocs-material mkdocs-glightbox mkdocs-autolinks-plugin
```

## Configuracion
El fichero de configuración es el mkdocs.yml


## Comandos

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs gh-deploy` - Despliega en github pages.
* `mkdocs -h` - Print help message and exit.

## Layout de ficheros

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
    site/         # Sitio generado en html
