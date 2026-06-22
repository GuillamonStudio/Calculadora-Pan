CALCULADORA DE PAN PARA IPHONE

Esta carpeta contiene una versión PWA de la calculadora.

Cómo instalarla en iPhone:
1. Sube esta carpeta a un hosting estático con HTTPS.
   Opciones sencillas: Netlify, Vercel, GitHub Pages o tu propio hosting.
2. Abre la URL desde Safari en el iPhone.
3. Pulsa Compartir.
4. Elige "Añadir a pantalla de inicio".
5. Se abrirá como una app independiente.

Archivos:
- index.html: calculadora principal
- manifest.json: configuración de app instalable
- sw.js: caché para uso offline
- icons/: iconos de la app

Nota:
Para que funcione como app instalable, iOS necesita abrirla desde Safari mediante una URL segura HTTPS. Abrir el archivo local directamente no permite instalarla como PWA.
