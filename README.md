Descripción
Este proyecto es un compilador desarrollado en NetBeans que realiza el análisis sintáctico y léxico de archivos escritos en C#. El objetivo principal de este compilador es leer archivos C#, analizar su estructura y generar una representación que pueda ser utilizada para diferentes fines, como la verificación de sintaxis o la transformación de código.

Características
Análisis Léxico: Identificación de tokens como palabras clave, identificadores, operadores, literales, etc.
Análisis Sintáctico: Verificación de la estructura del código fuente basado en las reglas gramaticales de C#.
Manejo de errores: Detección y reporte de errores léxicos y sintácticos.
Requisitos del Sistema
Java Development Kit (JDK) versión 8 o superior
NetBeans IDE versión 11 o superior
Instalación
Clonar el repositorio:

bash
Copiar código
git clone https://github.com/tu-usuario/tu-repositorio.git
Abrir el proyecto en NetBeans:

Abre NetBeans IDE.
Selecciona File > Open Project.
Navega hasta el directorio donde clonaste el repositorio y selecciona la carpeta del proyecto.
Construir el proyecto:

En NetBeans, haz clic derecho sobre el proyecto en el panel de proyectos y selecciona Clean and Build.
Uso
Agregar un archivo C#:

Coloca el archivo C# que deseas analizar en el directorio input del proyecto.
Ejecutar el compilador:

En NetBeans, haz clic derecho sobre el proyecto en el panel de proyectos y selecciona Run.
Resultados:

El compilador leerá el archivo C# desde el directorio input, realizará el análisis léxico y sintáctico y generará los resultados en el directorio output.
Estructura del Proyecto
src: Contiene el código fuente del compilador.
input: Directorio donde se deben colocar los archivos C# a analizar.
output: Directorio donde se generarán los resultados del análisis.
lib: Librerías adicionales necesarias para el compilador (si las hubiera).
Contribuciones
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature-nueva-funcionalidad).
Realiza tus cambios y haz commit de los mismos (git commit -am 'Agregar nueva funcionalidad').
Sube tus cambios a tu fork (git push origin feature-nueva-funcionalidad).
Crea un Pull Request explicando los cambios que has realizado.
