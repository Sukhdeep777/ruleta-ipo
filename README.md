# Ruleta Aleatoria 🎲

## Descripción
Esta ruleta permite seleccionar al azar uno o varios participantes para torneos, sorteos o actividades educativas.  
El proyecto está pensado para ser interactivo y visual, mostrando los nombres seleccionados con animaciones y GIFs de celebración.

## Funcionalidades
- Selección aleatoria de 1 a 5 personas.
- Animación tipo ruleta para simular el sorteo.
- Mensajes divertidos y aleatorios para los seleccionados.
- GIF de celebración junto a la ruleta.
- Panel lateral para agregar nombres manualmente.
- Posibilidad de **cargar nombres desde archivos**:
  - `.txt` (uno por línea o separados por comas)
  - `.csv` (uno por línea o separados por comas)
  - `.xls` / `.xlsx` (Excel, se toman los nombres de la primera columna de la primera hoja)
- Mantiene los nombres predeterminados si no se agregan otros.

## Tecnologías utilizadas
- **HTML**: estructura de la página.
- **CSS**: estilos, animaciones y diseño visual.
- **JavaScript**: lógica de selección aleatoria, animación de la ruleta y lectura de archivos.
- **SheetJS (xlsx.js)**: librería para leer archivos Excel directamente en el navegador.

## Cómo usar
1. Abrir el archivo `index.html` en un navegador moderno.
2. Seleccionar el número de personas a elegir con el desplegable.
3. Agregar nombres de alumnos en el panel lateral **uno por línea**, o subir un archivo `.txt`, `.csv` o Excel `.xls` / `.xlsx`.
4. Presionar el botón **"Girar Ruleta 🎲"**.
5. Ver los nombres seleccionados aparecer en la ruleta, junto con un mensaje divertido y un GIF de celebración.

## Referencias
- **ChatGPT**: ayuda en la lógica y desarrollo del proyecto.
- **Google**: búsqueda de GIFs animados.
- **Pixabay**: imágenes libres para recursos visuales.
- **SheetJS**: para lectura de archivos Excel en el navegador.

## Licencia
Este proyecto fue creado con fines educativos. Los GIFs y recursos utilizados respetan las licencias correspondientes.
