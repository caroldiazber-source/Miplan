# Miplan
App de nutrición y entrenamiento para el móvil (PWA: se instala desde el navegador, funciona sin conexión).

## Pestañas
- **Hoy**: menú del día, checklist y entreno del día.
- **Menú**: menú semanal editable y notas por semana.
- **Fechas**: días y comidas libres.
- **Progreso**: peso, cintura, gráfica y copia de seguridad (exportar/importar).
- **Entreno**: rutina de cada día de la semana.

## Publicarla (GitHub Pages)
1. En GitHub: *Settings → Pages → Source: Deploy from a branch*, rama `main`, carpeta `/ (root)`.
2. Abre `https://<tu-usuario>.github.io/Miplan/` en el móvil.

## Instalarla en el móvil
- **iPhone (Safari)**: botón Compartir → *Añadir a pantalla de inicio*.
- **Android (Chrome)**: menú ⋮ → *Instalar aplicación*.

Los datos se guardan en el teléfono. Usa **Progreso → Exportar** de vez en cuando como copia de seguridad.

Al cambiar archivos, sube `VERSION` en `sw.js` para que el móvil descargue la nueva versión.
