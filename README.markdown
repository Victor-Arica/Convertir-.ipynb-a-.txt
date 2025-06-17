# Convertidor de Jupyter Notebook a Texto (.txt)

## Descripción
Este proyecto contiene un script de Python que convierte un archivo Jupyter Notebook (.ipynb) en un archivo de texto plano (.txt). El script extrae el contenido de las celdas de tipo "markdown" y "code" del notebook y lo guarda en un archivo de texto, separando cada celda con dobles saltos de línea para facilitar la lectura. 

Esta herramienta es útil para:
- Archivar el contenido de un notebook en un formato más universal.
- Compartir el contenido con usuarios que no tienen acceso a Jupyter.
- Extraer texto para análisis o procesamiento adicional.
- Crear versiones de texto plano para revisiones o envíos donde los archivos .ipynb no son aceptados.

## Uso
1. Coloca el archivo Jupyter Notebook que deseas convertir (por ejemplo, `Matrices.ipynb`) en el mismo directorio que el script.
2. Ejecuta el script:
3. El archivo de salida (por ejemplo, `pregunta3.txt`) se generará automáticamente en el mismo directorio.

**Nota:** El script está configurado para convertir específicamente `Matrices.ipynb` a `pregunta3.txt`. Para convertir un notebook diferente, modifica las variables `ipynb_file_path` y `txt_output_path` al inicio del script.

## Estructura de Archivos
- **`convert_notebook.ipynb`**: Script principal que realiza la conversión del notebook a texto plano.
- **`Matrices.ipynb`**: Archivo de ejemplo de Jupyter Notebook (debe proporcionarse por el usuario).
- **`pregunta3.txt`**: Archivo de salida generado con el contenido extraído.
- **`README.md`**: Documentación del proyecto (este archivo).

## Cómo Funciona
El script realiza los siguientes pasos:
1. Carga el archivo .ipynb como un archivo JSON.
2. Recorre las celdas del notebook, extrayendo el contenido de las celdas de tipo "markdown" y "code".
3. Escribe el contenido extraído en un archivo .txt, separando cada celda con dobles saltos de línea (`\n\n`).


## Contribuciones
Si deseas contribuir al proyecto:
- Fork el repositorio.
- Realiza tus cambios en una rama nueva.
- Envía un pull request con tus mejoras.

## Contacto
Para reportar problemas o solicitar ayuda, abre un issue en el repositorio de GitHub o contacta al autor en [victorarica1000@gmail.com].
