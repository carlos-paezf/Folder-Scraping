# Folder Scraping

Este script está diseñado para analizar archivos en un directorio específico y recopilar metadatos sobre ellos. También proporciona la capacidad de filtrar archivos por su extensión y realizar ciertas comprobaciones sobre los nombres de archivo y las rutas.

## Funcionalidad

El script realiza las siguientes tareas:

- Recopila metadatos sobre los archivos en un directorio específico, como el tamaño del archivo, la fecha de modificación, la longitud del nombre, etc.
- Permite filtrar archivos por su extensión, si se proporciona una lista de extensiones permitidas.
- Realiza comprobaciones sobre los nombres de archivo y las rutas para determinar si cumplen ciertos criterios, como la presencia de palabras clave, extensiones permitidas, validez del nombre de archivo, etc.
- Guarda los metadatos recopilados en un archivo Excel para su posterior análisis.

## Uso

Para usar el script, sigue estos pasos:

1. Configura el directorio base (`base_directory`) en el que quieres analizar los archivos.
2. Configura la ruta del archivo Excel (`excel_file_path`) donde se guardarán los resultados del análisis.
3. Opcionalmente, puedes definir un conjunto de extensiones permitidas para filtrar los archivos que se analizarán.
4. Ejecuta el script escribiendo `python script.py`.
5. Los resultados del análisis se guardarán en el archivo Excel especificado.

## Mejoras Posibles

Aquí hay algunas mejoras potenciales que podrían realizarse para mejorar la funcionalidad del script:

- Agregar más comprobaciones sobre los nombres de archivo y las rutas para cubrir más casos de uso.
- Mejorar la estructura del código para hacerlo más modular y fácil de mantener.
- Proporcionar opciones de configuración adicionales, como la capacidad de especificar carpetas de exclusión o criterios de búsqueda avanzados.
- Agregar soporte para otros formatos de archivo de salida, como CSV o JSON, además del archivo Excel.

¡Siéntete libre de contribuir al proyecto enviando solicitudes de extracción o sugiriendo nuevas características!
