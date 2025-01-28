# PDFTOCSV_withPython

# Proyecto: Extracción de Datos desde un PDF y Conversión a CSV

Este repositorio contiene un ejemplo práctico de cómo extraer datos desde un archivo PDF y convertirlos a un formato CSV utilizando Python. Además, se incluye un código adaptado para ejecutarse en Google Colab.

## Descripción

El proyecto aborda el siguiente caso:

1. Extraer información tabular desde un PDF público proporcionado por el "Comité de Evaluación del Poder Judicial de la Federación".
2. Convertir dicha información a un archivo CSV que pueda abrirse y manipularse en Excel o Google Sheets.
3. Proveer un script que puede ejecutarse en entornos locales o en Google Colab.

## Archivos

- **script\_local.py**: Contiene el código para ejecutar el proceso en un entorno local.
- **script\_colab.ipynb**: Contiene el código listo para ejecutarse en Google Colab.
- **README.md**: Este archivo, que describe el proyecto.

## Requisitos

### Ejecución Local

1. Python 3.7 o superior.
2. Instalar las siguientes librerías:
   ```bash
   pip install PyPDF2 pandas





Ejecución en Google Colab
No es necesario instalar dependencias adicionales, ya que la mayoría están preinstaladas. Solo necesitas cargar tu archivo PDF o usar un enlace público.

Uso
Ejecución Local
Asegúrate de que el archivo PDF esté en el mismo directorio que el script o especifica su ruta.
Ejecuta el script con el siguiente comando:
bash
Copiar
Editar
python script_local.py
El archivo CSV generado se guardará en el mismo directorio con el nombre output.csv.
Ejecución en Google Colab
Abre el archivo script_colab.ipynb en Google Colab.
Carga tu archivo PDF en la sesión de Colab o utiliza un enlace público.
Ejecuta las celdas en orden para procesar el archivo y descargar el CSV generado.
Ejemplo de Enlace Público
Si deseas usar un PDF disponible públicamente, puedes probar con este enlace: CEPL-Aspirantes.pdf.

Notas
Asegúrate de que el archivo PDF tenga permisos públicos si está en la web.
El código está diseñado para tablas simples. Si el formato del PDF es complejo, podrían requerirse ajustes adicionales.
Contribuciones
Si tienes sugerencias o mejoras para este proyecto, no dudes en hacer un fork y enviar un pull request.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más información.

¡Gracias por usar este proyecto! Si tienes alguna pregunta, no dudes en abrir un issue.
