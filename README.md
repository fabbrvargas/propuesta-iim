# Propuesta de posicionamiento de marca — IIM Promotora Inmobiliaria

Microsite estático de Splash Labs con la propuesta de servicio de contenido recurrente
($1.000 mensuales · servicio continuo) para IIM Promotora Inmobiliaria.
HTML, CSS y JavaScript puros: sin frameworks, sin build step, sin analytics ni cookies.
Única dependencia externa: Google Fonts (Cormorant Garamond e Instrument Sans).

## Estructura

```
index.html            página única
styles.css            estilos (mobile-first, incluye @media print)
main.js               barra al hacer scroll, fade-in, videos por viewport, visor, imprimir
favicon.svg / apple-touch-icon.png
robots.txt + meta noindex
.nojekyll
assets/img/           fotos optimizadas, posters y og.jpg (vista previa al compartir)
assets/video/         portada (hero-h / hero-v), previews livianos y versiones completas
```

## Antes de enviar

Completar las variables marcadas en naranja en `index.html`:

- `[VOCERO]` — persona de IIM que aparece en cámara, con cargo (aparece 2 veces)
- `[APROBADOR]` — persona de IIM que aprueba calendario y piezas (aparece 1 vez)

## Despliegue en GitHub Pages

1. Subir el contenido de esta carpeta a la raíz de un repositorio (por ejemplo `propuesta-iim`).
2. **Settings → Pages → Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. Queda en `https://<usuario>.github.io/<repo>/` en uno o dos minutos.

Las etiquetas Open Graph usan URLs absolutas a `https://fabbrvargas.github.io/propuesta-iim/`;
si cambia el repo, actualizarlas para que la vista previa en WhatsApp muestre la imagen.

## Créditos de imagen

- Videos y fotogramas: trabajo previo de Splash Labs para San Patricio, rotulados como tal.
- Fotografías de ambientación: Freepik (licencia de la cuenta de Splash Labs), rotuladas como stock.
