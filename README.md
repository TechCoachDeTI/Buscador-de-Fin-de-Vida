🔍 Buscador de Ciclos de Vida (EOL)

Este es un proyecto simple y funcional de una sola página HTML que utiliza la API pública de endoflife.date para buscar y mostrar información sobre los ciclos de vida (End-of-Life, EOL) de diversos productos de software y hardware. Es una herramienta útil para planificadores y técnicos que necesitan verificar rápidamente el estado de soporte de un producto.

✨ Características

Búsqueda en Tiempo Real: Obtiene datos directamente de la API endoflife.date.

Diseño Responsivo: Utiliza Tailwind CSS para un diseño moderno y adaptable a móviles.

Normalización Robusta: Incluye lógica para normalizar las entradas de búsqueda del usuario, mejorando las tasas de éxito de la API.

Vistas por Perfil: Ofrece dos modos de visualización:

Público General: Muestra un resumen simple y las fechas clave.

Técnico: Muestra todos los ciclos de vida disponibles con detalles técnicos (versiones, fechas de mantenimiento, etc.).

Autocompletado (Experimental): Sugerencias de productos cargadas al inicio para facilitar la búsqueda.

🛠️ Tecnología

HTML5: Estructura.

Tailwind CSS (CDN): Estilos y responsive design.

JavaScript (Vanilla): Lógica de la aplicación y manejo de la API.

API: https://endoflife.date/api/

🚀 Uso Local

Dado que es un único archivo HTML con dependencias de CDN, es muy fácil de ejecutar:

Guarda el contenido de eol_date_finder.html como index.html.

Abre el archivo index.html directamente en tu navegador.

No requiere servidor web.

🐛 Debugging y Robustez

El código incluye:

Mecanismo de Retry con Exponential Backoff para manejar fallos temporales de red en las llamadas a la API.

Manejo explícito de errores HTTP 404.
