# Plantilla — Ejercicio práctico Parcial 1 (Versión B)

## Cómo correrlo

Es un proyecto estático (HTML + CSS + JS por CDN), no necesita servidor ni build:

1. Abre `index.html` directamente en el navegador (doble clic, o "Open with Live Server" si usas VS Code).
2. TheMealDB (`https://www.themealdb.com/api/json/v1/1/...`) es pública y usa la key de prueba `1`, ya incluida en las URLs de la plantilla.

## Qué hacer

Ver las instrucciones completas en `../Parcial1-Evaluacion-VersionB.md`, Parte 2. Todo el trabajo va dentro de los bloques marcados `TODO` en `index.html`, más el archivo `styles.css`.

## Cómo probar la persistencia con localStorage

1. Busca una receta.
2. Recarga la página (F5).
3. El resultado de la búsqueda debe seguir apareciendo, sin que se dispare una nueva llamada a la API (podés confirmarlo en la pestaña Network de DevTools).
4. Usa el botón "Borrar búsqueda guardada" y recarga de nuevo: ahora no debería quedar nada en `#resultado`.
