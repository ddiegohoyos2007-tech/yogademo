# Diagnóstico inicial — Estudio Mareas (Barranco, Lima)

Fecha: 18/11/2026. Capturas en 375, 768 y 1440 px y Lighthouse móvil en esta carpeta.

## Estructura
- Un solo archivo `index.html` con CSS y JS propios, sin framework ni build.
- Fuentes: Bricolage Grotesque + DM Sans (Google Fonts, con `display=swap`).
- Imágenes: **ninguna** (0 etiquetas `<img>`). Solo una ola en SVG detrás del titular y un favicon en SVG.
- Vercel: no hay `vercel.json`; se publica como sitio estático. El repo no tiene rama `main`.

## Puntajes Lighthouse móvil (antes)
Rendimiento 99 · Accesibilidad 96 · Buenas prácticas 100 · SEO 100.

## Qué está bien
- Contenido completo: 4 clases, horario por día con cupos y filtros, 4 planes, preguntas frecuentes y botón flotante de WhatsApp.
- Rápido y liviano; cuidado móvil (zona segura del notch, botones táctiles).

## Qué se ve genérico o roto
- Sin fotos: no muestra el estudio, las máquinas ni a las instructoras. La tipografía sans no transmite calma ni cuidado.
- Contraste insuficiente en la etiqueta "hoy" de los días (falla de Lighthouse).
- En los botones de horario, el nombre accesible no coincide con el texto visible.
- **El pie de página dice que nombres, precios y horarios son ficticios.** Hay que confirmar los datos reales antes de presentarlo como sitio de un cliente.
- Falta: imagen Open Graph, schema.org, sitemap.xml y robots.txt.
- No hay secciones de instructoras ni de galería.

## Dónde faltan imágenes
1. Hero (sala con reformers con luz natural).
2. Tipos de clase: reformer, mat, vinyasa, restaurativo (una por clase).
3. El estudio (detalle de espacio y materiales).
4. Secciones nuevas: instructoras, galería del estudio, Open Graph (1200×630).
No sobra ninguna imagen.
