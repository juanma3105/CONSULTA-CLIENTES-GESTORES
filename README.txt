# Consulta de Clientes - Gestores

Web-app móvil para buscar un cliente por `CDCLI`.

## Incluye
- Código y nombre del cliente
- Nombre del transportista
- Teléfono del transportista
- Dirección
- Latitud y longitud
- Botón para llamar al transportista
- Botón para abrir la ubicación en Google Maps
- Diseño responsive para celular

## Publicación
Sube los archivos `index.html`, `data.js` y `manifest.webmanifest` a un hosting estático como GitHub Pages, Netlify o Cloudflare Pages.

IMPORTANTE: `data.js` contiene la base de clientes, teléfonos y coordenadas. No publiques esta versión en un sitio público sin protección/acceso autorizado. Para uso interno de gestores, conviene añadir autenticación o publicar en un entorno privado.

## Actualización
Cuando cambie el Excel, se debe volver a generar `data.js` desde la hoja `PROGRAMACION`.
