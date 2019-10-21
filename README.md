# hyperblog  
Un blog increíble para el curso de Git y Github de Platzi.

## ¿Qué es un Sistema Control de Versiones?
Un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo. Este tipo de sistemas nos permiten volver en el tiempo y salvar nuestro trabajo.

Los tipos de sistemas de control son:

- ** Local Computer: **Solo vive en nuestro computador.
- **Centralizado: **No depende únicamente de un computador en el que se trabaja, sino que depende del súper servidor en donde se almacena la información. El servidor provee las copias a sus hijos, pero solo guarda los cambios en un solo lugar.
- **Sistema de control distribuidos:** Cada uno de los que participan en el proyecto, tienen copia del proyecto que se realiza, por eso no dependemos de un solo computador que almacene toda la información.

Git es un Sistema de Control de Versiones Distribuido creado por *Linus Torvalds*  y se centró en:

*1. <u>Velocidad.</u>*
Que puedas trabajar fluidamente desde tu computador.

*2. <u>Diseño sencillo.</u>*
Herramientas necesarias para tomar acción en el VCS a través de código robusto, como viajar en el tiempo.

*3. <u>Fuerte apoyo en el desarrollo no lineal.</u>*
Una de las características más increíble de Git. No es necesario seguir un camino predefinido para trabajar, es decir, puedes crear otras cosas que no estaban definidas. Al final, en algún punto las podrás agregar a tu proyecto.

*4. <u>Completamente distribuido.</u>*
Esto da la ventaja de que cada quien tenga su propio repositorio. Haciendo que el repositorio principal sea casi imposible perderlo.

*5. <u>Capaz de manejar grandes proyectos.</u>*
Puede manejar proyectos tan grandes como Linux.<br><br>

### ¿Qué diferencia a Git de los otros VCS?
Mientras otros VCS solo almacenan los cambios existentes dentro de los archivos. Git lo que hace además de lo anterior es que si no le hiciste un cambio a un archivo te crea un enlace a ese archivo en lugar de guardarlo otra vez. Esto hace a Git muy rápido para moverse en el tiempo.
<br>

###### Casi cualquier trabajo que hagas en Git es local. 
Es decir que puedes trabajar de modo offline sin miedo. Esto porque tienes un repositorio en tu computador. Cuando tengas conexión puedes guardar los cambios (Commits en Git).<br><br>

###### Git tiene integridad. 
No puedes perder información durante su transmisión o sufrir corrupción de archivos sin que Git lo detecte.<br><br>


### ¿Cómo almacena Git los cambios?
En un SHA-1, que es una función hash que a partir del contenido de un archivo o su estructura de directorios, genera una cadena de 40 caracteres hexadecimales que harán una referencia a uno de los cambios realizado en el proyecto. Básicamente en Git todo se verifica mediante un checksum antes de ser almacenado y el mecanismo utilizado para generar este checksum es el hash SHA-1 calculado con base en el contenido del archivo o su estructura de directorio. Esto es lo que le da integridad e impide que se hagan cambios sin que Git lo note.<br>

------------

## Los tres estados de Git

Git tiene tres estados principales en los que se pueden encontrar tus archivos:
###### Confirmado (committed)
Confirmado significa que los datos están almacenados de manera segura en tu base de datos local. <br><br>
###### Modificado (modified)
Modificado significa que has modificado el archivo pero todavía no lo has confirmado a tu base de datos. <br><br>
###### Preparado (staged)
Preparado significa que has marcado un archivo modificado en su versión actual para que vaya en tu próxima confirmación.<br><br>
Las tres secciones principales de un proyecto de Git son las siguientes:
###### Working Directory: 
Es donde trabajamos de manera local, pero para guardarlo hay que pasarlo al Staging Area.<br><br>
###### Staging Area: 
Es el área de preparación, se almacenan justo antes de hacer commit.<br><br>
###### Git Repository: 
El repositorio donde almacenaremos los cambios del proyecto.<br><br>

