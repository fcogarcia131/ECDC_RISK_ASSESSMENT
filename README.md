# App Evaluación Rápida de Riesgos ECDC

Esta carpeta contiene una app web instalable tipo PWA para móvil y PC.

## Uso rápido

1. Abre `index.html` en Chrome, Edge o Safari.
2. Rellena metadatos, escenario, preguntas y observaciones.
3. Usa:
   - **Generar resumen** para ver vacíos de información.
   - **Exportar informe** para copiar el informe completo.
   - **Generar PDF / Imprimir** para abrir una versión imprimible. En el cuadro de impresión selecciona **Guardar como PDF**.
   - **Descargar TXT** para guardar una copia en texto plano.

## Instalación como app

Para que el modo app/offline funcione correctamente, sube esta carpeta a un servidor HTTPS, GitHub Pages, Netlify o similar. Luego:

- PC Chrome/Edge: abre la URL y pulsa **Instalar**.
- Android Chrome: menú ⋮ > **Añadir a pantalla de inicio** o **Instalar app**.
- iPhone Safari: botón compartir > **Añadir a pantalla de inicio**.

## Nota sobre PDF

El botón **Generar PDF / Imprimir** usa la impresión nativa del navegador. Esto es más compatible y no necesita librerías externas. En la ventana de impresión elige **Guardar como PDF**.
