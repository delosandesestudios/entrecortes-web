# Web EntreCortes — Catering de carnes

Sitio de una sola página, autocontenido: el archivo `index.html` ya trae las
tipografías (Ultra + Montserrat), las fotos y todo el código dentro.
No necesita servidor, ni base de datos, ni dependencias.

## Qué contiene

- Portada, servicios, paquetes, menú a la carta, cotizador, eventos,
  testimonios, qué incluye, preguntas frecuentes y cierre con WhatsApp.
- Cotizador: invitados (15 a 4.000), ciudad, fecha, adicionales y logística.
  Calcula total, promedio por plato y kilos de proteína, y arma el mensaje de
  WhatsApp con la palabra COTIZAR.
- Dos líneas de WhatsApp: 0424-781.7241 (principal) y 0414-720.1370 (alterna).

## Publicar en Vercel (2 formas)

### A. Desde la web (la más fácil, sin instalar nada)

1. Entra a https://github.com y crea una cuenta (o inicia sesión).
2. Arriba a la derecha: **New repository**. Nombre: `entrecortes-web`.
   Déjalo público y pulsa **Create repository**.
3. En el repositorio: **Add file → Upload files**. Arrastra `index.html`
   (y este README.md). Pulsa **Commit changes**.
4. Entra a https://vercel.com y pulsa **Sign up → Continue with GitHub**.
5. En Vercel: **Add New… → Project → Import** el repositorio
   `entrecortes-web` → **Deploy**.
6. En menos de un minuto te da una dirección tipo
   `entrecortes-web.vercel.app`. Esa es la web, ya en internet.

### B. Con la terminal (si alguien del equipo prefiere)

```bash
npm i -g vercel
vercel login
vercel --prod
```

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
