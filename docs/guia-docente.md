# Guía docente

## Intención pedagógica

Este proyecto NO busca que el alumno copie una landing terminada.

Busca que tome decisiones sobre:

- estructura
- contenido
- jerarquía visual
- estilos
- comportamiento

La base está guiada, pero no resuelta.

## Clase 1

### Objetivo

Que el alumno construya la primera versión de su perfil profesional usando HTML, CSS y Bootstrap.

### Secuencia sugerida

1. explicar el objetivo del proyecto final
2. recorrer `index.html` y ubicar las secciones base
3. trabajar el `header` y la navegación
4. construir `#presentacion`
5. desarrollar `#sobre-mi`
6. armar `#habilidades`
7. dejar encaminado `#proyectos`
8. cerrar con `footer`

### Conceptos a remarcar

- HTML semántico antes que apariencia
- CSS como capa de presentación
- Bootstrap como acelerador, no como reemplazo de fundamentos
- contenido real antes que lorem ipsum eterno

### Resultado mínimo esperado

- header funcional
- navegación interna básica
- una presentación principal clara
- al menos una sección desarrollada con contenido real
- estructura general completa aunque falten detalles

### Tarea sugerida

- terminar la página
- mejorar responsive
- completar proyectos
- revisar consistencia visual

## Clase 2

### Objetivo

Incorporar comportamiento con JavaScript sobre el sitio construido en la primera clase.

### Secuencia sugerida

1. abrir `src/main.js`
2. explicar selección de elementos del DOM
3. agregar un formulario en `#contacto`
4. escuchar evento `submit` o `click`
5. validar campos
6. mostrar mensajes en pantalla
7. sumar una interacción extra

### Interacciones recomendadas

- validación de formulario
- menú hamburguesa simple
- botón mostrar/ocultar más información
- filtro de habilidades o proyectos

### Conceptos a remarcar

- JavaScript agrega comportamiento, no estructura
- primero seleccionar bien el DOM, después modificar
- no abusar de `innerHTML` si no entienden qué están haciendo
- cada interacción debe tener un propósito claro

## Archivo por archivo

### `index.html`
- estructura del sitio
- punto principal de trabajo de la clase 1

### `src/styles/main.css`
- estilos propios mínimos
- espacio para reforzar selectores, box model y organización visual

### `src/main.js`
- punto principal de trabajo de la clase 2
- espacio para DOM, eventos y validaciones

## Decisiones didácticas tomadas

- se evitó una app demasiado completa
- se eliminó la arquitectura modular previa porque resolvía demasiado
- se dejó un starter estándar, más cercano a cómo arranca un proyecto real chico

## Sugerencia de dinámica

- 20% explicación
- 40% construcción guiada
- 40% práctica del alumno con acompañamiento

No conviene convertir la clase en una demo eterna del docente. Tienen que tocar el código.
