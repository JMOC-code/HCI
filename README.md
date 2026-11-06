# ViveLocal

ViveLocal es una propuesta de aplicación web/móvil orientada a facilitar el descubrimiento de eventos culturales cercanos, como conciertos, obras de teatro, exposiciones o actividades en museos.

El proyecto ha sido desarrollado como parte de la asignatura de Diseño de Interacción, prestando especial atención a la usabilidad, la accesibilidad y la coherencia visual de la interfaz.

## Objetivo

El objetivo principal de ViveLocal es ofrecer una experiencia sencilla e intuitiva para que los usuarios puedan:

- Consultar eventos culturales cercanos.
- Filtrar eventos por categoría, fecha o ubicación.
- Acceder al detalle de cada actividad.
- Guardar eventos de interés.
- Navegar fácilmente entre las principales secciones de la aplicación.

## Diseño y prototipado

El proceso de diseño se ha desarrollado de forma progresiva, comenzando por wireframes en blanco y negro y evolucionando posteriormente hacia una propuesta visual completa en color.

El diseño se ha trabajado en Figma, donde se encuentran:

- Sistema visual.
- Wireframes iniciales.
- WireFrames Color_Prueba1
- Propuesta visual final de las principales pantallas.

### Prototipo en Figma

https://www.figma.com/design/FZtuNsKy3q9BoTKzLkyIUv/ViveLocal

## Accesibilidad

Como complemento al prototipo desarrollado en Figma, se creó una versión web simplificada de la pantalla principal mediante HTML y CSS.

Esta versión permitió realizar una evaluación práctica de distintos aspectos de accesibilidad, entre ellos:

- Estructura semántica del documento.
- Jerarquía de encabezados.
- Etiquetas asociadas a formularios.
- Uso de atributos ARIA.
- Navegación mediante teclado.
- Visibilidad del foco.
- Adaptación responsive.
- Contraste entre texto y fondo.

La evaluación se realizó mediante WAVE.

En el primer análisis se detectaron dos problemas de contraste. Tras revisar la paleta cromática y sustituir el color secundario `#8E5BB7` por un tono más oscuro (`#7A469F`), se volvió a realizar el análisis.

El resultado final obtenido con WAVE fue:

- 0 errores.
- 0 errores de contraste.
- 0 alertas.
- 9 elementos estructurales identificados.
- 20 elementos y atributos ARIA reconocidos.
- AIM Score: 10/10.

También se realizó una comprobación manual de la navegación mediante teclado y del comportamiento responsive de la interfaz.

## Estructura del repositorio

```text
ViveLocal/
│
├── index.html
├── styles.css
│
├── img/
│
├── evidencias-accesibilidad/
│   ├── WAVE1.png
│   ├── Errores_inicales.png
│   ├── Contrast-Error_inicial.png
│   ├── Contrast-Error_inicial_2.png
│   ├── Detalle_Contrast-Error_inicial.png
│   └── WAVE_Mejora_1.png
│
└── README.md
```

## Tecnologías y herramientas utilizadas

- HTML5
- CSS3
- Figma
- WAVE Web Accessibility Evaluation Tool
- GitHub

## Criterios de diseño

La propuesta se ha desarrollado siguiendo criterios básicos de:

- Coherencia visual.
- Navegación clara.
- Jerarquía de la información.
- Legibilidad.
- Diseño responsive.
- Accesibilidad.
- Reducción del número de pasos necesarios para realizar las tareas principales.

Se han tomado como referencia los principios generales de accesibilidad recogidos en WCAG 2.1.

## Contenido del repositorio

Este repositorio contiene los archivos utilizados como apoyo técnico al proyecto ViveLocal.

La implementación HTML/CSS no pretende reproducir toda la funcionalidad de una aplicación final, sino servir como una versión simplificada de la interfaz que permita comprobar de forma práctica determinadas decisiones de diseño y accesibilidad realizadas durante el proyecto.

## Proyecto académico

Proyecto realizado para la asignatura de Diseño de Interacción.