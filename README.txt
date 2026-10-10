ENTRECORTES — Sitio web (v5, identidad de marca aplicada)
=========================================================

Qué es: una sola página HTML autocontenida. No necesita build, ni
dependencias, ni internet: las tipografías (Alfa Slab One + Montserrat),
las fotos, el logo y el favicon van incrustados en el archivo.

CÓMO PUBLICARLO EN VERCEL (3 minutos)
-------------------------------------
Opción A — sin instalar nada (recomendada):
  1. Entra a https://vercel.com/new
  2. Arrastra esta carpeta completa (o solo el archivo index.html) al área
     de carga.
  3. Vercel detecta un sitio estático. Deja todo por defecto y pulsa Deploy.
  4. Te da una URL tipo entrecortes.vercel.app. Se puede conectar un dominio
     propio después, en Settings > Domains.

Opción B — con la CLI:
  npm i -g vercel
  cd entrecortes-deploy
  vercel          (preview)
  vercel --prod   (producción)

QUÉ FALTA PARA PUBLICAR EN FIRME
--------------------------------
- Precios reales (hoy: referencia de $20 por plato).
- Fotos propias de eventos (hoy: imágenes de referencia estilo dark & moody).
- Capturas de testimonios reales.
- Dominio definitivo.

EDITAR
------
Abre index.html con cualquier editor de texto. Los datos del menú y los
paquetes están en el bloque "var MENU = {" y "var PACKAGES = {" al final
del archivo. El número de WhatsApp está en "var WHATSAPP = ".
