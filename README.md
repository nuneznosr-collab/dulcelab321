# Pasaporte Digital DulceLab Navidad 2026

Aplicación web estática e independiente. No contiene tienda, catálogo comercial, carrito ni pedidos.

## Publicación en Render (Static Site)
1. Sube el contenido de esta carpeta a un repositorio GitHub (los archivos `index.html`, `styles.css`, `app.js` y `README.md` deben quedar en la raíz).
2. En Render elige **New + → Static Site** (NO Web Service).
3. Conecta el repositorio.
4. Configura:
   - Build Command: dejar vacío (si Render exige un valor, usar `echo static`).
   - Publish Directory: `.`
5. Crea el sitio.

No selecciones Docker ni Dockerfile. El error `failed to read dockerfile` aparece cuando se crea un Web Service con entorno Docker, no cuando se publica como Static Site.

## Accesos QR
Las cinco rutas se pueden abrir como enlaces directos con hash, compatibles con hosting estático:
- `https://TU-DOMINIO/#/pasaporte/gingerbread`
- `https://TU-DOMINIO/#/pasaporte/cookie`
- `https://TU-DOMINIO/#/pasaporte/choco`
- `https://TU-DOMINIO/#/pasaporte/cupcake`
- `https://TU-DOMINIO/#/pasaporte/brownies`

Cuando tengas el dominio definitivo, genera un QR distinto para cada URL anterior. No uses un QR hasta reemplazar `TU-DOMINIO` por la dirección real.

## Funciones implementadas
- Cinco experiencias con tutoriales y actividades interactivas.
- Diseñador visual sencillo para cada línea.
- Juego de preguntas con puntuación.
- Progreso local e insignias desbloqueables al completar tutorial, diseño y desafío.
- Galería local de fotos (no se suben a servidores).
- Certificado imprimible/guardable como PDF desde el navegador.
- Diseño responsive.

## Datos y límites
El progreso y las fotos se guardan en el almacenamiento local del navegador. Si se borran los datos del navegador o se cambia de dispositivo, pueden perderse. No se han inventado cantidades, proporciones, tiempos, temperaturas ni fechas de conservación; para esos datos se debe seguir el instructivo físico validado por DulceLab. Las fotografías remotas son imágenes ilustrativas de Unsplash y pueden sustituirse por fotografías propias antes de publicar.
