# Prolici - Sitio Web Corporativo

Este repositorio contiene el código fuente del sitio web corporativo de Prolici (Proyectos Ligeros Civiles), una empresa de construcción dominicana especializada en proyectos de construcción ligera y acabados de alta calidad.

## Estructura del Sitio

El sitio web consta de las siguientes páginas:

- **Inicio (index.html)**: Página principal con información general sobre la empresa.
- **Nosotros (nosotros.html)**: Información sobre la historia, equipo, misión, visión y valores de la empresa.
- **Servicios (servicios.html)**: Detalle de los servicios ofrecidos por la empresa.
- **Proyectos (proyectos.html)**: Galería de proyectos realizados por la empresa.
- **Contacto (contacto.html)**: Formulario de contacto e información de contacto.

## Tecnologías Utilizadas

- HTML5
- CSS3 (con Flexbox y Grid para layouts)
- JavaScript (vanilla)
- Font Awesome para iconos
- Google Maps para el mapa de ubicación

## Estructura de Archivos

```
/
├── index.html              # Página de inicio
├── nosotros.html           # Página sobre nosotros
├── servicios.html          # Página de servicios
├── proyectos.html          # Página de proyectos
├── contacto.html           # Página de contacto
├── css/
│   └── styles.css          # Estilos principales
├── js/
│   └── main.js             # JavaScript principal
├── img/
│   ├── placeholder.html    # Generador de imágenes placeholder
│   ├── hero-bg.jpg         # Imagen de fondo para hero section
│   ├── servicio-*.jpg      # Imágenes para servicios
│   ├── proyecto*.jpg       # Imágenes para proyectos
│   └── team-*.jpg          # Imágenes para equipo
└── README.md               # Este archivo
```

## Personalización

### Colores

Los colores principales del sitio se basan en la identidad corporativa de Prolici:

- Verde primario: `#00A651`
- Negro: `#000000`
- Blanco: `#FFFFFF`
- Gris claro (fondo): `#f8f8f8`
- Gris oscuro (texto): `#333333`

Para cambiar estos colores, edite el archivo `css/styles.css`.

### Imágenes

Las imágenes utilizadas en el sitio son placeholders y deben ser reemplazadas con imágenes reales antes de la publicación. Se ha incluido un generador de imágenes placeholder (`img/placeholder.html`) para facilitar el desarrollo.

Para reemplazar las imágenes:

1. Prepare imágenes de alta calidad en los tamaños recomendados.
2. Reemplace los archivos en la carpeta `img/` manteniendo los mismos nombres.

### Contenido

Para actualizar el contenido del sitio:

1. Edite los archivos HTML correspondientes a cada página.
2. Actualice los textos, manteniendo la estructura HTML existente.
3. Para añadir nuevos proyectos, duplique los bloques de código correspondientes en `proyectos.html`.

## Formulario de Contacto

El formulario de contacto en `contacto.html` está configurado para validación del lado del cliente, pero no tiene funcionalidad de envío real. Para implementar el envío de formularios, se recomienda:

1. Configurar un servicio de formularios como Formspree, Netlify Forms o similar.
2. Alternativamente, implementar un backend para procesar los formularios.

## Optimización para Producción

Antes de publicar el sitio en producción, se recomienda:

1. Optimizar las imágenes para web (compresión, tamaño adecuado).
2. Minificar los archivos CSS y JavaScript.
3. Implementar carga diferida (lazy loading) para imágenes.
4. Configurar un certificado SSL para HTTPS.

## Mantenimiento

Para mantener el sitio actualizado:

1. Actualice regularmente la información de contacto si cambia.
2. Añada nuevos proyectos a medida que se completen.
3. Actualice la sección de servicios si se añaden nuevos servicios.
4. Mantenga actualizada la información del equipo.

## Compatibilidad con Navegadores

El sitio está diseñado para ser compatible con los siguientes navegadores:

- Google Chrome (últimas 2 versiones)
- Mozilla Firefox (últimas 2 versiones)
- Safari (últimas 2 versiones)
- Microsoft Edge (últimas 2 versiones)

## Licencia

© 2025 Prolici - Proyectos Ligeros Civiles. Todos los derechos reservados.
