## **Challenge 3: Procesamiento de datos de TelecomX**

Este es mi tercer desafío aprendiendo ciencia de datos. En este proyecto, me enfoqué en conectar Python con una fuente de datos externa en internet, descargar la información y convertirla en una tabla ordenada para poder analizarla.

**Descripción del proyecto**

El objetivo principal de este cuaderno de Google Colab fue extraer los datos crudos (en formato JSON) de los clientes de una empresa ficticia llamada TelecomX. Una vez descargados desde un repositorio en línea, utilicé la librería Pandas para transformarlos en un DataFrame. Esto es el primer paso fundamental antes de poder hacer cualquier limpieza de datos, buscar patrones o crear gráficos.

**Proceso realizado paso a paso**
Para completar este desafío, seguí una secuencia lógica de trabajo en Python:

- Extracción automatizada: Utilicé la librería requests para conectar el cuaderno directamente con la fuente de datos en GitHub. Esto asegura que el análisis siempre trabaje con la versión más reciente del archivo.

- Conversión a estructura de datos: Transformé el formato JSON original en un DataFrame de Pandas, logrando que la información se visualice como una tabla organizada.

- Exploración y limpieza: Revisé la estructura de la tabla para entender qué tipo de información contenía cada columna y asegurarme de que no hubiera errores de formato.

- Informe de variables y análisis: Realicé un estudio de los datos para extraer conclusiones sobre los clientes de la empresa.

**Análisis de las variables (Informe)**

Una vez estructurados los datos, me centré en analizar los siguientes puntos clave:

- Perfil de los clientes: Analicé variables como el nombre, género y ubicación para entender quiénes son los usuarios de TelecomX.

- Comportamiento de consumo: Revisé las columnas de uso de datos y minutos para identificar qué clientes tienen un consumo más alto y cuáles están en planes básicos.

- Estado de los servicios: Estudié la variable de "estatus" de la suscripción para ver cuántos clientes están activos, cancelados o suspendidos.

- Análisis de antigüedad: Observé cuánto tiempo llevan los clientes en la compañía, lo que permite identificar la fidelidad de los usuarios.

- Relación plan-costo: Comparé los tipos de planes contratados con el monto facturado para verificar si los ingresos son coherentes con los servicios prestados.

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
