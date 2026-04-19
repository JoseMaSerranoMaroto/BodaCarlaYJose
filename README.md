# Boda Carla & Jose

Web informativa para la boda de Carla y Jose, diseñada con una estetica de festival indie y preparada para publicarse facilmente en GitHub Pages o en cualquier hosting estatico.

## Que incluye

- Pantalla de entrada con ticket interactivo
- Hero principal con cuenta atras para el 6 de febrero de 2027
- Seccion de detalles del evento y cronograma
- Galeria de imagenes
- Pie de pagina moderno con contacto integrado
- Musica de prueba generada por JavaScript
- Diseño responsive para movil y escritorio

## Estructura del proyecto

```text
.
├── index.html
├── styles.css
└── assets/
    ├── audio/
    └── images/
```

## Como verlo en local

Al ser una web estatica, puedes abrir `index.html` directamente en el navegador.

Si prefieres servirlo localmente:

```bash
python3 -m http.server 8000
```

Despues abre `http://localhost:8000`.

## Personalizacion rapida

- Imagen de entrada: `assets/images/entrada.png`
- Fondo principal: `assets/images/fondoVertical.png`
- Vinilo: `assets/images/vinilo.png`
- Estilos: `styles.css`
- Contenido y secciones: `index.html`

## Musica

Ahora mismo el proyecto usa una melodia de prueba generada con JavaScript.

Si mas adelante quieres cambiarla por un archivo real, puedes adaptar el bloque de audio en `index.html` y guardar el archivo en `assets/audio/`.

## Publicacion en GitHub

Pasos recomendados:

1. Crear un repositorio en GitHub.
2. Subir estos archivos.
3. Si quieres publicarlo como web, activar GitHub Pages desde la rama principal.

## Licencia

Este proyecto no incluye licencia todavia. Si quieres permitir reutilizacion por terceros, conviene elegir una licencia de forma explicita antes de publicarlo.
