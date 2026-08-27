# Portfolio — Esteban Chiabrando

Portfolio personal hecho con HTML, CSS y Bootstrap 5.3.

## Páginas

| Archivo | Contenido |
|---|---|
| `index.html` | Inicio: presentación, foto y datos personales |
| `sobre-mi.html` | CV: experiencia, proyectos, tecnologías, formación e idiomas |
| `trabajos.html` | Proyectos: carrusel y detalle en acordeón |
| `contacto.html` | Formulario de contacto y datos directos |

## Estructura

```
├── index.html
├── sobre-mi.html
├── trabajos.html
├── contacto.html
├── css/
│   └── estilos.css      Paleta de colores y estilos propios
└── imgs/                Imágenes
```

## Tecnologías

- HTML5
- CSS3
- Bootstrap 5.3.8 (vía CDN)
- Bootstrap Icons 1.11.3

## Notas

El formulario de contacto es una maqueta: valida los campos con Bootstrap
pero todavía no envía los mensajes a ningún lado.

Los colores están centralizados en `css/estilos.css`, sobrescribiendo las
variables CSS de Bootstrap. No hace falta recompilar Sass para cambiarlos.
