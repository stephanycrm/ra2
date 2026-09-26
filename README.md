# 🚀 Tech Mission

Experiencia web educativa interactiva para Licenciatura en Tecnología.

## Incluye
- Campaña de 6 misiones y retos.
- Realidad aumentada con cámara + marcador Hiro.
- Explorador 3D.
- Modo accesible sin cámara.
- Carpeta `models/` preparada para modelos `.glb`/`.gltf`.

## Subir modelos de Sketchfab / Free3D
Descarga solo modelos cuya licencia permita reutilización. Preferiblemente usa `.glb`. Colócalos en `models/` y sustituye los modelos didácticos de ejemplo por `gltf-model="models/tu-modelo.glb"`. Mantén autor, URL y licencia en `CREDITOS_MODELOS.md`.

## Cámara y GitHub Pages
La RA necesita HTTPS o localhost. GitHub Pages sirve el sitio con HTTPS. No abras `ar.html` directamente con `file://`. En el celular pulsa **Activar cámara** y acepta el permiso.

## Publicación
1. Crea un repositorio en GitHub.
2. Sube el contenido de esta carpeta manteniendo las subcarpetas.
3. Settings → Pages → Deploy from branch → `main` → `/root`.
4. Abre la URL HTTPS generada.

## Base técnica
A-Frame + AR.js para la RA y modelos 3D. La estructura está pensada para aprendizaje basado en retos, exploración, resolución de problemas y competencias tecnológicas.
