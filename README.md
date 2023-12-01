# DAW


## Tipos de Texto

### 1. Bloques de texto preformateado
Los bloques de texto preformateado se logran utilizando cuatro espacios al inicio de la línea.

    Esto es un bloque de texto preformateado.
    Se conserva el formato exacto, incluyendo espacios y saltos de línea.

### 2. Notas o Advertencias
> **Nota:** Este es un mensaje de nota o advertencia que resalta información importante.

### 3. Texto tachado
~~Este texto está tachado.~~

**Texto en negrita**



*Texto en cursiva*



### 6. Imágenes y gif
![Descripción de la imagen](descarga.jpeg)

![Descripción del gif](18313506.gif)

### 7. Íconos o Emoji
Puedes utilizar íconos o emoji como 😀🚀💻 para añadir visualizaciones.

### 8. Superíndices y subíndices
El superíndice se logra con ^superíndice y el subíndice con ~subíndice~.

### 9. Letra capitular
Utiliza un signo de mayor que (>) seguido del carácter para hacer una letra capitular: >E.

### 10. Acordes musicales
Puedes mostrar acordes musicales: C, Dm, G, Am.

### 11. Texto justificado
<span style="text-align: justify;">Este es un texto justificado. Se ajusta a los márgenes.</span>


## Uso de restricciones en `.gitignore`

El archivo `.gitignore` en un repositorio de Git permite especificar archivos o patrones de archivos que se deben ignorar en el control de versiones. Aquí se describen tres tipos de restricciones comunes:

1. **Restricciones de Archivo Específico**: 
   Se pueden ignorar archivos específicos proporcionando el nombre del archivo en el `.gitignore`. Por ejemplo:



2. **Restricciones por Patrón**: 
Se pueden ignorar múltiples archivos que coincidan con un patrón específico utilizando comodines como `*` para representar cualquier secuencia de caracteres y `**` para directorios. Por ejemplo:



3. **Restricciones por Carpeta o Directorio**: 
Además de archivos específicos, se pueden ignorar todos los archivos dentro de un directorio especificado utilizando `/nombre-del-directorio/`. Por ejemplo:


## Teoría de Git

Git es un sistema de control de versiones distribuido que facilita el seguimiento de cambios en el código fuente durante el desarrollo de software. Algunos conceptos fundamentales incluyen:

- **Repositorio**: Almacén de archivos y el historial de cambios.
- **Commit**: Instantánea de los cambios realizados en los archivos.
- **Ramas (Branches)**: Versiones paralelas del repositorio para desarrollar características o aislar cambios.
- **Fusiones (Merges)**: Combinación de ramas para integrar cambios.
- **Conflictos**: Situaciones en las que se requiere resolver diferencias entre versiones de archivos.

Git proporciona una infraestructura sólida para la colaboración en proyectos, el seguimiento de cambios y la gestión eficiente del código fuente.
