# Integradora-Práctica02
Práctica de clase para comenzar a utilizar GitHub como herramienta para el desarrollo colaborativo, control de versiones y documentación det proyecto integrador de la asignatura.

## Comandos Básicos para el Maquetado

### 1.0 Encabezados (Headings) 
Para poder dar enfásis a los contenidos de la documentación podemos utilizar los encabezados (Headings), para marcar alguna sección o subsección estos se marcan utilizando el símbolo #, entre menos repeticiones tenga mayor tamaño e importancia tendrá el texto.


Ejemplo:
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6 
####### Encabezado nivel 7 (Solo considera los primeros 6 niveles)

### 2. Separados (SEPARATORS) - PRÁCTICA 03 
Si desea marcar una separación más visual de contenidos podemos utlizarlos indicando tres caracteres de "_" continuos, en el maquetado

EJEMPLO:
"Esto es similar a un tag de <HR> en HTML.




### 3. Párrafos (PARAGRPAHS)
Son utilizados para poder presentar grandes secciones de texto que describen detalladamente las secciones de la documentación del proyecto.

EJEMPLO: 

Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al parrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1.

Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al parrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Estetexto pertenece al parrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2

Lo que en una página utilizariamos usando la etiqueta < p >.

También podemos aplicar estilos básicos de alineación: 

Este párrafo está alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto 

<p align="right">
Este párrafo esta alineado a la derecha utilizando la propiedad alineación.Este párrafo esta alineado a la derecha utilizando la propiedad alineación.Este párrafo esta alineado a la derecha utilizando la propiedad alineación.Este párrafo esta alineado a la derecha utilizando la propiedad alineación.Este párrafo esta alineado a la derecha utilizando la propiedad alineación.
</p>

<p align="center" >
Este párrafo esta centrado usando la propiedad de alineación.Este párrafo esta centrado usando la propiedad de alineación.Este párrafo esta centrado usando la propiedad de alineación.Este párrafo esta centrado usando la propiedad de alineación. Este párrafo esta centrado usando la propiedad de alineación.Este párrafo esta centrado usando la propiedad de alineación.
</p>

<p align="justify">
Este párrafo esta centrado usando la propiedad de justificado.Este párrafo esta centrado usando la propiedad de justificdo.Este párrafo esta centrado usando la propiedad de justificado.Este párrafo esta centrado usando la propiedad de justificado. Este párrafo esta centrado usando la propiedad de justificado.Este párrafo esta centrado usando la propiedad de justificado.
</p>

### 4. Texto enfatizado (BOLD, ITALIC, BOLD/ITALIC) 
Si el texto que deseamos enfatizar se encuentra en un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.

##### Texto en Negrita (BOLD) 
Para poder poner el texto en negrita, se deberá ser encerrado entre dobles * *

EJEMPLO: 

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto **Texto** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto


##### Texto en cursiva (ITALIC) 
Algunas veces es necesario resaltar algunas secciones o textos en cursiva para que el lector detecte el texto importante, dentro del maquetado con el estándar Markdown lo podemos realizar ubicando el texto entre * (asteriscos).

**EJEMPLO:**

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto

##### Texto en Negrita y Crusiva (BOLD & ITALIC) 

De igual manera podemos unir ambos estilos **Negrita** y *Cursiva* para resaltar los textos que consideremos importantes dentro de la documentación de nuestros proyectos de Software, utilizando un triple * (asterisco).

EJEMPLO: 

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto en Negrita y Cursiva*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto

##### Subrayado (UNDERLINE) 

Algunas veces necesitaremos subrayas texto dentro de la documentación, para ello, si bien Markdown no tiene un atajo o codificación rápida podemos utilizar el estilo estándar de HTML usando el tag <ins> y cerrando con </ins> 

EJEMPLO:

Texto Textl Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins> Texto Subrayado</ins> Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

### 5. Cuadros para codigos o reseñas (BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones especificas para la instalacion, configuracion y/o inicializacion o mostra
secciones de codigo fuente. Se maqueta iniciando el texto con un simbolo de mayor que (\>)

**Ejemplo**
Para listar las carpetas y archivos en desde una terminal de sistema operativo Windows debemos ingresar el comando:

>C:/dir

Despues oprimimos la tecla "Enter"

Tambien podemos agregar texto multilinea 

**Ejemplo**

>Aqui se ingresan un conjunto de instrucciones para explicar al usuario, como instalar el software que hemos diseñado

Y si deseamos incluir viñetas para enlistar pasos podemos utilizar el caracter - dentro del tecto a documentar-

*Ejemplo: Pasos para instalar la Base de Datos: *

> - Descargar MySQl Server del Sitio Oficial
> - Intalar el sistema gestor de base de datos, definiendo el puerto y contraseña para el usuario "**root**"
> - Descargamos el archivo de respaldo de la base de datos (.sql) 
> -  Restauramos la Base de Datos usando el comando "Mysql"

### 7. Ligas e hipervinculos 

Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizando los corchetes [], inmediatamente despues 
podremos la liga de referencia entre parentecis

*Ejemplo: * Mi buscador favorito es [Google](https://www.google.com.mx/?hl=es)

Pero si deseamos poner solo las ligas directas o un correo electronico podemos utilizar los simbolos <>

Documentacion creada por: *Derek Sesni Carreño*<dereksesni6@gmail.com>


### 8. Tabla (TABLES)

Si la documentación lo requiere podemos presentar información en formato de tabla con filas y columnas, para maquetarlas podemos utilizar el carácter \| para delimitar las columnas y \- para delimitar las filas.

**EJEMPLO:**

|Encabezado 1| Encabezado 2| Encabezado 3| Encabezado 4|
|----------------------| -----------------------| -----------------------| ----------------------|
|Fila 1 Celda 1| Fila 1 Celda 2| Fila 1 Celda 3| Fila 1 Celda 4|
|Fila 2 Celda 1| Fila 2 Celda 2| Fila 2 Celda 3| Fila 2 Celda 4|
|Fila 3 Celda 1| Fila 3 Celda 2| Fila 3 Celda 3| Fila 3 Celda 4|

En caso de necesitar la fusión de celdas en columnas usaremos la propiedad colspan del Tag <td> y en el caso de necesitar la fusión de filas utilizaremos la propiedad rowspan.

**EJEMPLO:**

|Encabezado 1| Encabezado 2| Encabezado 3| Encabezado 4|
|----------------------| ------------------------| -----------------------|----------------------|
|Fila 1 Celda 1| Fila 1 Celda 2| Fila 1 Celda 3| Fila 1 Celda 4|
|Fila 2 Celda 1<td colspan> Fila 2 Celda 2| Fila 2 Celda 3|
|Fila 3 Celda 1| Fila 3 Celda 2| Fila 3 Celda 3| Fila 3 Celda 4|
|              | Fila 4 Celda 2| Fila 4 Celda 3| Fila 4 Celda 4|
|              | Fila 5 Celda 2| Fila 5 Celda 3| Fila 5 Celda 4|
|Fila 6 Celda 1| Fila 6 Celda 2| Fila 6 Celda 3| Fila 6 Celda 4|

Dado que en el ejemplo pasado usando solo markdown no se puede realizar la fusión de filas, debemoss utilizar el estándar HTML, usando los tags: \<th> para los encabezados, \<tr> para las filas y <td> para las celdas, y en ellos utilizar la propiedad de "colspan" y "rowspan". 
