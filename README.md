# Menú digital — Delicious Trémens

Menú digital **100% estático**: sin servidor, sin base de datos, sin
dependencias. Todo lo que necesita está en esta carpeta.

## Publicar

**En el hosting del restaurante:** sube el CONTENIDO de esta carpeta a la
carpeta pública del hosting (por FTP/cPanel). Listo.

**En GitHub Pages:** crea un repo (p. ej. `menu_tremens`),
sube estos archivos a la rama `main` y activa Settings → Pages → rama main.
El menú queda en `https://<usuario>.github.io/<repo>/`.

## Probar en local

```bash
npx serve .        # o: python3 -m http.server 8080
```

(Abrir el index.html directo con file:// no funciona: el menú se carga
por fetch y los navegadores lo bloquean fuera de un servidor.)

## Actualizar el menú

Esta versión es una foto del menú al 28 de septiembre de 2026.
Para actualizarla se vuelve a generar desde MenuOS y se re-sube la carpeta.

---
Generado por MenuOS · `tools/export/estatico.ts tremens`
