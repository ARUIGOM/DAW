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

Del ejercicio 3º   este son los tres tipos de restricción de guin 
* se usa para encontrar coincidencias
/ se usa para ignorar nombres de ruta relacionados con el archivo .gitignore
# se usa para añadir comentarios al archivo .gitignore


Este es el ejercicio 4º

**GIT:** Es un software de control de versiones diseñado pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. Su propósito es llevar registro de los cambios en archivos de PC incluyendo coordinar el trabajo que varias personas realizan sobre archivos compartidos en un repositorio de código.
*El diseño de Git* mantiene una enorme cantidad de código distribuida y gestionada por mucha gente, que incide en numerosos detalles de rendimiento, y de la necesidad de rapidez en una primera implementación.
Entre las características más relevantes se encuentran:
- Fuerte apoyo al desarrollo no lineal, por ende rapidez en la gestión de ramas y mezclado de diferentes versiones. Git incluye herramientas específicas para navegar y visualizar un historial de desarrollo no lineal.

- Gestión distribuida. Git le da a cada programador una copia local del historial del desarrollo entero, y los cambios se propagan entre los repositorios locales. Los cambios se importan como ramas adicionales y pueden ser fusionados en la misma manera que se hace con la rama local.
- Almacenamiento de la información menos pesada debido al guardado de cambios y no de archivos completos.

- Los almacenes de información pueden publicarse.

- Gestión eficiente de proyectos grandes, dada la rapidez de gestión de diferencias entre archivos, entre otras mejoras de optimización de velocidad de ejecución.

- Compatibilidad con una amplia gama de herramientas de desarrollo.

+ Existen muchas órdenes de git que nos sirven para realizar diferentes funcionalidades:

1. git init: Esto crea un subdirectorio nuevo llamado .git, el cual contiene todos los archivos necesarios del repositorio – un esqueleto de un repositorio de Git. Todavía no hay nada en tu proyecto que esté bajo seguimiento.

2. git fetch: Descarga los cambios realizados en el repositorio remoto. Comprueba el estado del repositorio local en comparación con el repositorio remoto.

3. git merge: Impacta en la rama en la que te encuentras parado, los cambios realizados en la rama “nombre_rama”.

4. git pull: Unifica los comandos fetch y merge en un único comando.

5. git commit: Confirma los cambios realizados. El “mensaje” generalmente se usa para asociar al commit una breve descripción de los cambios realizados.

6. git push: Sube la rama “nombre_rama” al servidor remoto.

7. git status: Muestra el estado actual de la rama, como los cambios que hay sin commitear.
