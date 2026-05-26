# Curso Web con Vite + Vanilla JS

Proyecto base para enseñar fundamentos de desarrollo web construyendo un **perfil profesional / CV web** con:

- HTML
- CSS
- Bootstrap
- JavaScript
- Vite

## Estructura actual

```txt
src/
  styles/
    main.css
  main.js
```

- `index.html`: estructura semántica base del perfil profesional
- `src/styles/main.css`: estilos propios mínimos
- `src/main.js`: punto de entrada para agregar comportamiento en clase 2

La idea es que cada estudiante tome esta base y la complete paso a paso durante la cursada.

## Propuesta pedagógica

Documentación complementaria:

- `docs/consigna-alumnos.md`
- `docs/guia-docente.md`

### Clase 1
- completar `header`, navegación, secciones principales y `footer`
- trabajar HTML semántico
- sumar CSS propio
- usar Bootstrap para acelerar layout y espaciados

#### Recorrido sugerido en clase 1
1. completar identidad básica del perfil en el `header`
2. convertir `#presentacion` en una sección principal fuerte
3. desarrollar `#sobre-mi` con texto real del estudiante
4. construir `#habilidades` con listas, badges o cards
5. dejar `#proyectos` empezado aunque no quede terminado en clase
6. cerrar con un `footer` simple y prolijo

### Tarea
- terminar la página del perfil profesional
- mejorar contenido, estilos y responsive
- completar la sección `#proyectos`
- revisar navegación interna y consistencia visual

### Clase 2
- agregar comportamiento con JavaScript
- trabajar DOM y eventos
- sumar validación o interacción en la sección de contacto

#### Recorrido sugerido en clase 2
1. crear selectores del DOM en `src/main.js`
2. agregar un formulario en `#contacto`
3. validar campos vacíos o email
4. mostrar mensajes de éxito o error
5. sumar una interacción extra: menú, filtros o botón mostrar/ocultar

## Mapa del HTML base

- `#presentacion`: hero o presentación principal
- `#sobre-mi`: biografía, estudios o experiencia
- `#habilidades`: stack, herramientas o fortalezas
- `#proyectos`: trabajos destacados o portfolio
- `#contacto`: formulario e interacciones de JavaScript

La idea no es que el alumno rellene placeholders sin pensar. La idea es que use este mapa como guía para tomar decisiones de estructura y contenido.

## Recomendación para GitHub

Conviene que cada alumno cree un **repositorio propio** a partir de esta base en lugar de trabajar solo sobre un fork, así sus commits cuentan mejor como actividad en su perfil y además les queda una pieza propia de portfolio.

## Scripts

- `pnpm dev`: inicia el entorno de desarrollo
- `pnpm build`: genera la carpeta `dist`
- `pnpm preview`: previsualiza el build localmente
- `pnpm lint`: ejecuta ESLint
- `pnpm lint:fix`: corrige problemas simples automáticamente

## Gestión de dependencias

- el proyecto usa `pnpm`
- las versiones en `package.json` están fijadas sin `^`
- `.npmrc` define `save-exact=true` para mantener ese criterio

## GitHub Pages

El proyecto ya incluye:

- `vite.config.js` con `base: './'` para rutas relativas
- workflow en `.github/workflows/deploy.yml`

### Pasos para publicar

1. Subí el proyecto a un repositorio en GitHub.
2. Hacé push a la rama `main`.
3. En GitHub, andá a **Settings > Pages**.
4. En **Build and deployment**, elegí **GitHub Actions**.
5. El workflow va a compilar y publicar el contenido automáticamente.
