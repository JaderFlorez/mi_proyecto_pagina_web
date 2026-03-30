# Sitio web estático — Portfolio profesional

Sitio web personal desarrollado desde cero con **HTML5, CSS3 y JavaScript vanilla**, sin frameworks ni librerías externas. Diseñado como portfolio digital con navegación entre secciones, video de fondo en el hero, formulario de contacto funcional y diseño responsive.

Desarrollado como proyecto práctico de maquetación web y diseño de interfaces estáticas.

## Funcionalidades

- Navegación con anclas a secciones internas (header fijo)
- Hero con video de fondo (`<video>`) y overlay de texto
- Sección "Sobre mí" con foto de perfil y descripción biográfica
- Sección de servicios con tarjetas de contenido
- Sección de proyectos/experiencia con imágenes destacadas
- Formulario de contacto funcional via **FormSubmit** (sin backend propio)
- Footer con enlaces a redes sociales
- Diseño responsive con CSS puro

## Stack tecnológico

- **HTML5** — estructura semántica con secciones, nav, footer
- **CSS3** — flexbox, variables CSS, media queries, animaciones
- **Google Fonts** — tipografía Inter
- **Font Awesome** — íconos vectoriales
- **FormSubmit** — envío de formularios sin servidor propio

## Estructura del proyecto

```
mi_proyecto_pagina_web/
├── index.html
├── styles.css
└── contenido_multimedia/
    ├── foto_perfil.jpeg
    ├── logo.png
    ├── video_hero.mp4
    ├── proyecto1.jpeg
    ├── proyecto2.jpeg
    ├── proyecto3.png
    └── proyecto4.jpeg
```

## Cómo ejecutar

Es un sitio completamente estático — no requiere servidor ni instalación:

```bash
git clone https://github.com/JaderFlorez/mi_proyecto_pagina_web.git
cd mi_proyecto_pagina_web
# Abrir index.html directamente en el navegador
```

Para desarrollo con recarga automática se puede usar la extensión **Live Server** de VS Code.

## Aprendizajes aplicados

- Estructura semántica HTML5 (nav, main, section, footer)
- Maquetación con Flexbox
- Uso de variables CSS para paleta de colores consistente
- Integración de servicios externos sin backend (FormSubmit)
- Organización de activos multimedia en proyectos web

## Autor

**Jader Andrés Flórez López**  
Backend Developer| Medellín, Colombia  
[LinkedIn](https://www.linkedin.com/in/jader-florez) · [GitHub](https://github.com/JaderFlorez)
