# coreframework-custom-styles-mcd

Custom Styles para Transformadores MCD usando Core Framework.

## ¿Qué incluye?

- **colores-mcd.css**: paleta institucional y utilidades de fondo/estado.
- **breakpoints-mcd.css**: variables responsivas para padding, gaps y tipografía.
- **tipografia-mcd.css**: estilos de texto base y jerarquía de títulos.
- **secciones-mcd.css**: contenedores, secciones y tarjetas reutilizables.
- **botones-mcd.css**: estilos para CTAs principales, secundarios y de texto.

## Cómo usar

1. Importa las variables base primero:

   ```html
   <link rel="stylesheet" href="colores-mcd.css">
   <link rel="stylesheet" href="breakpoints-mcd.css">
   ```

2. Agrega los componentes que necesites (tipografía, secciones, botones, etc.).
3. Combina utilidades: por ejemplo `.fondo-primario + .texto-oscuro` para contraste adecuado.

## Recomendaciones

- Mantén el orden de importación para que las variables estén disponibles en todos los componentes.
- Verifica el contraste de colores al combinar fondos y textos para cumplir criterios de accesibilidad.
- Usa las clases de botones con `:focus-visible` para asegurar navegación con teclado.
- Si tu proyecto requiere menos movimiento, habilita `prefers-reduced-motion` en tu navegador para desactivar transiciones.
- Aprovecha los estados `:disabled` o `aria-disabled="true"` en los botones para evitar interacciones involuntarias; los estilos ya incluyen cursores y opacidades acordes.
- Conserva la tipografía heredada (`font-family` y `font-size`) de tu proyecto: los botones respetan esos valores para mantener consistencia visual.
