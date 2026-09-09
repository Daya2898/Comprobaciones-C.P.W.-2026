# -Comprobaciones-C.P.W.-2026
Actividades de comprobación del módulo Codificación de Paginas Web.

## Patrones de Diseño Adaptativo Aplicados al sitio 

En este proyecto aplique distintos patrones de diseño adaptativo seleccionados estratégicamente según el tipo de contenido y el espacio disponible en cada pantalla:

- **Off-Canvas (Navegación):** En móvil (<768px), el menú se oculta tras un botón de hamburguesa nativo (`Checkbox Hack` en CSS) para ahorrar espacio. En pantallas más anchas (≥768px), se muestra en barra horizontal.
- **Column Drop (Tarjetas):** La sección de propuestas pasa de 1 columna en móvil a 2 en tabletas y 3 en escritorio.
- **Mostly Fluid (Galería y Secciones):** La rejilla ajusta sus columnas según el tamaño de la pantalla (1 a 4 columnas) y limita su ancho máximo a `118rem` para evitar deformaciones.
- **Tiny Tweaks (Tipografía):** Los títulos (`h1`, `h2`, `h3`) ajustan su tamaño con `rem` en cada punto de quiebre para mantener la jerarquía visual.
