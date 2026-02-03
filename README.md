1. Justificación basada en la Ley de Fitts
Para los controles de zoom y los botones de confirmación, se aplicaron los siguientes ajustes:

Tamaño de los botones: Se incrementó el área de clic en los elementos de la lista lateral y los popups para facilitar la interacción en dispositivos táctiles.

Posicionamiento: Los botones de control se mantuvieron en áreas de fácil alcance, evitando esquinas extremas que resultan incómodas en pantallas de gran formato.

2. Gestión de la Densidad de Información
Se implementó un sistema de marcadores temporales.

Un marcador solo se convierte en permanente tras la confirmación del usuario, evitando que el mapa se llene de "clics accidentales".

3. Registro de Prompts (Refinamiento)
Prompt Maestro: "Genera un archivo HTML que incluya Leaflet.js y Tailwind CSS. Crea un contenedor div 'map' que ocupe el 100% del ancho y 600px de alto. Inicializa el mapa centrado en Ensenada. Asegúrate de que los controles sean legibles y que el menú lateral no bloquee la visión central del mapa."

4. Estructura de Rutas
Ruta /mapa: Renderiza el archivo templates/index.html integrando la lógica de Leaflet con el backend de Flask.
