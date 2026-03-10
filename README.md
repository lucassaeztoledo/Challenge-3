- Challenge 3: Procesamiento de datos de TelecomX
Este es mi tercer desafío aprendiendo ciencia de datos. En este proyecto, me enfoqué en conectar Python con una fuente de datos externa en internet, descargar la información y convertirla en una tabla ordenada para poder analizarla.

**Descripción del proyecto**
El objetivo principal de este cuaderno de Google Colab fue extraer los datos crudos (en formato JSON) de los clientes de una empresa ficticia llamada TelecomX. Una vez descargados desde un repositorio en línea, utilicé la librería Pandas para transformarlos en un DataFrame. Esto es el primer paso fundamental antes de poder hacer cualquier limpieza de datos, buscar patrones o crear gráficos.

**Qué aprendí haciendo esto**
Como estudiante, este proyecto me ayudó a poner en práctica:

*Peticiones web:* Usar la librería requests para comunicarme con una URL y traer datos directamente a mi código, sin tener que descargar el archivo manualmente a mi computadora.

*Estructuras de datos:* Entender cómo se lee un archivo JSON.

*Manejo de Pandas:* Convertir esa información desordenada en un DataFrame (una tabla estructurada con filas y columnas), que es la herramienta base del análisis de datos en Python.

**Tecnologías utilizadas**
*Python:* Lenguaje de programación base.

*Pandas:* Para la creación y visualización del DataFrame.

*Requests:* Para consumir los datos desde la web.

*Google Colab:* Como entorno de desarrollo y ejecución en la nube.

**Cómo ejecutar este proyecto**
- Si quieres probar mi código, solo necesitas seguir estos pasos:

- Abre el archivo challenge-3.ipynb en tu propio entorno de Google Colab o Jupyter Notebook.

- Asegúrate de que las librerías necesarias estén instaladas. (En Colab suelen venir por defecto, pero puedes asegurarte corriendo !pip install pandas requests).

- Ejecuta las celdas en orden de arriba hacia abajo. El código se conectará a la URL, descargará el archivo TelecomX_Data.json y te mostrará la tabla con los datos estructurados.
