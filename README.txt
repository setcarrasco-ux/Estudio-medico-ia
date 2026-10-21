ESTUDIO MÉDICO IA — PROTOTIPO INICIAL
=====================================

QUÉ INCLUYE
- Interfaz web móvil en español.
- Generador local de guion base mediante plantilla.
- Guardado de proyectos en el navegador.
- Copiar guion y exportar proyectos como JSON.
- Consejos para preparar foto y voz del avatar.

IMPORTANTE
Este prototipo NO genera todavía un avatar hiperrealista ni es un APK nativo.
Está diseñado para ser el primer paso de una solución Android de costo cero.
No introduzcas información identificable de pacientes.
Los guiones son plantillas y deben ser revisados clínicamente antes de publicar.

CÓMO PROBARLO SOLO CON ANDROID
Opción A — Prueba rápida:
1. Descomprime el ZIP en tu teléfono con un gestor de archivos.
2. Abre index.html con un navegador compatible.
   Algunas funciones como el modo instalable y el guardado pueden depender del navegador.

Opción B — Instalarlo como aplicación web (PWA):
1. Sube estos archivos a un repositorio GitHub desde el navegador móvil.
2. En GitHub, activa Settings > Pages y publica desde la rama principal / raíz.
3. Abre la URL HTTPS que GitHub Pages te proporcione en Chrome Android.
4. Menú ⋮ > Añadir a pantalla de inicio / Instalar aplicación.
La publicación de un sitio estático en GitHub Pages tiene una opción gratuita. La interfaz de GitHub puede variar.

ARCHIVOS
- index.html: interfaz y lógica.
- manifest.json: configuración PWA.
- sw.js: caché básica para uso offline.
- README.txt: estas instrucciones.

PRÓXIMA FASE
Añadir un flujo para cargar audio y video del avatar, y conectar una herramienta de generación solo después de comprobar que ofrece un plan gratuito o una API utilizable sin costo.
