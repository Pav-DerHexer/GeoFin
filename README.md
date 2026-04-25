"# GeoFin" 
https://pav-derhexer.github.io/Criptomaneras/


Masthead estilo periódico clásico con el nombre "GeoFin"
  - Post destacado (el más reciente, 23 abr) con formato grande y etiqueta "Nuevo"                                        - Posts anteriores con fecha a la izquierda (día/mes/año) y cuerpo a la derecha
  - Etiquetas de categoría en color: azul marino para Geopolítica, verde para Finanzas                                    - Mismo sistema de diseño que tus posts (Playfair Display + IBM Plex Sans, fondo papel crema)
  - Totalmente responsivo para móvil
  - Cada tarjeta es un enlace directo al archivo HTML del post
  
  Qué hace cada pieza:
  - Redirect raíz: detecta navigator.language del navegador y redirige automáticamente. Si el idioma no está soportado,
  cae a es/. La etiqueta <meta http-equiv="refresh"> es el fallback para navegadores sin JS.
  - Selector de idioma: barra fina en la parte superior de todas las páginas — ES · EN · DE · HU — con el idioma activo
  subrayado en azul oscuro.
  - En artículos: el selector está integrado en la barra de navegación existente (← Inicio a la izquierda, selector a la
   derecha). Se oculta en móvil para no saturar la barra.
  - EN/DE/HU: páginas completas con el mismo diseño, mensaje nativo en cada idioma, y enlace de vuelta a la versión
  española.
  - hreflang: etiquetas en el <head> de todos los índices para SEO multilingüe correcto.

  Cuando traduzcas un artículo, solo tienes que crear el archivo en la carpeta del idioma correspondiente (ej.
  en/2026.04.23_Bitcoin.Soberanos.html) y actualizar el selector de idioma de ese artículo para que el enlace EN apunte
  al archivo en lugar de al índice.