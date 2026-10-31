# Migración de developer-portfolio a React

## Objetivo
Migrar progresivamente el portafolio actual (HTML, CSS y JavaScript) a React, conservando el diseño, contenido, enlaces y recursos visuales.

## Estado inicial
- Rama original: `master` (se conserva sin cambios).
- Rama de trabajo: `migration/react`.
- Proyecto actual: `index.html`, `styles.css`, `main.js`, `assets/` y `cv/`.
- Secciones: Inicio, Sobre mí, Capacidades, Stack principal, Certificaciones, Proyectos, Contacto y Footer.
- Interacciones: menú responsive, navegación por anclas y animaciones reveal al hacer scroll.

## Ruta de trabajo
1. Preparar React con Vite en la rama `migration/react`.
2. Configurar la estructura `src/components`, `src/sections`, `src/data` y `src/styles`.
3. Conservar los recursos existentes dentro de `public/assets` y `public/cv`.
4. Migrar el layout global y navegación.
5. Migrar las secciones a componentes React, una por una.
6. Sustituir los manejadores directos del DOM por estado, eventos y efectos de React.
7. Verificar responsive, enlaces, certificados, CV y animaciones.
8. Actualizar README y despliegue cuando la migración esté validada.

## Convenciones
- Componentes en PascalCase.
- Datos repetidos (capacidades, tecnologías, certificaciones y proyectos) en `src/data`.
- Usar rutas absolutas desde la raíz para recursos públicos, por ejemplo `/assets/programando.jpg`.
- Mantener CSS existente al principio; refactorizar estilos después de validar cada sección.
- No borrar la versión anterior de `master` ni alterar la rama principal durante la migración.

## Progreso
- [x] Revisar estructura y archivos principales.
- [x] Crear rama `migration/react`.
- [ ] Inicializar Vite + React.
- [ ] Migrar componentes y estilos.
- [ ] Validar y desplegar.
