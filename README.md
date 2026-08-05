# Visualizador de Bonos de Emergencia

Dashboard en vivo con KPIs, gráficos y tabla filtrable sobre los bonos de emergencia (fondos aprobados, transferidos y pendientes por región, tipo de bono, institución pagadora, analista y evento de emergencia).

## Fuente de datos

Los datos se leen directamente desde la planilla de Google Sheets cada vez que se carga la página (y se refrescan automáticamente cada 5 minutos):

https://docs.google.com/spreadsheets/d/1ex-GvI8Fb-hdctSe_qr_eNA5W_GLWNI6ql3kDYa8_fA/edit

Para que la página funcione, la planilla debe mantenerse compartida como "Cualquiera con el enlace puede ver".

## Uso

Este repositorio está pensado para publicarse con GitHub Pages (rama main, carpeta raíz). Una vez activado, la página queda disponible en:

https://ugre-grd.github.io/visualizador-bonos-emergencia/

## Tecnologías

- HTML/CSS/JS puro (sin build step)
- Chart.js para los gráficos
- Grid.js para la tabla filtrable
- Google Visualization API (JSONP) para leer la planilla sin backend
