# Web EntreCortes — Catering de carnes

Sitio de una sola página, autocontenido: el archivo `index.html` ya trae las
tipografías (Ultra + Montserrat), las fotos y todo el código dentro.
No necesita servidor, ni base de datos, ni dependencias.

**En vivo:** https://entrecortes-web.vercel.app

## Qué contiene

- Portada, servicios, paquetes, menú a la carta, cotizador, eventos,
  testimonios, qué incluye, preguntas frecuentes y cierre con WhatsApp.
- Cotizador: invitados (15 a 4.000), ciudad, fecha, adicionales y logística.
  Calcula total, promedio por plato y kilos de proteína, y arma el mensaje de
  WhatsApp con la palabra COTIZAR.
- Dos líneas de WhatsApp: 0424-781.7241 (principal) y 0414-720.1370 (alterna).

## Cómo se publica

El repositorio está conectado a Vercel. Para actualizar la web:

1. Se cambia `index.html`.
2. Se sube el cambio al repositorio (`git push`).
3. Vercel publica la nueva versión en uno o dos minutos.

- Repositorio: https://github.com/delosandesestudios/entrecortes-web
- Panel de Vercel: https://vercel.com/delosandesestudios-7637s-projects/entrecortes-web

No hay que volver a crear nada ni tocar la configuración de Vercel.

## Versiones

- **v10 (actual):** SEO local (titulares y datos estructurados), imagenes en WebP
  (26% mas livianas), boton flotante de cotizacion, pestanas del menu con contador
  y 4 platos por vista, adicionales avanzados en un desplegable, fecha del mensaje
  en palabras, contraste corregido en movil y galeria de eventos en testimonios.
  Incluye `lab.html`, el laboratorio de efectos, y `og.jpg` para las vistas previas.
- **v9:** grano de película y viñeta cinematográfica en todo el sitio,
  el sello se estampa en la portada al cargar, las secciones aparecen con un
  fundido al bajar, y visor de fotos a pantalla completa en la galería.
  Respeta la preferencia del sistema "reducir movimiento".
- **v8:** primera versión publicada. Blanco y negro puro, titulares en Ultra y
  texto en Montserrat, fotos y testimonios reales tomados del Instagram.

## Cambiar contenido más adelante

- Textos, precios del menú y paquetes: están dentro de `index.html`,
  en la parte de abajo, en los bloques `var MENU = {...}` y `var PKGS = {...}`.
- Si se cambia el archivo, se sube otra vez a GitHub y Vercel republica solo.

## Pendientes antes de usarla con clientes

- Confirmar los números de WhatsApp definitivos.
- Reemplazar los precios de referencia por los reales.
- Subir fotos originales de eventos (las de Instagram son portadas de Reels
  de 360 px: sirven en tarjetas, no para la portada).
- Dominio propio (por ejemplo entrecortes.com.ve) desde Vercel → Domains.
