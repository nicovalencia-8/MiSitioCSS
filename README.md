# HTML5

## **HEAD**

### `Tittle` 
Para poner un icono en el titulo de la página utilizamos la sentencia

link rel="shortcut icon" href="favicon.ico"

[Generar ico](https://www.favicon.cc/)

### `Fuente`
Para definir la fuente que vamos a utilizar podemos referenciarla desde la pagina de [Google Fonts](https://fonts.google.com/) utilizando la siguiente sentencia:

link href="https://fonts.googleapis.com/css2?family=Sacramento&display=swap" rel="stylesheet"

y en nuestro archivo css la definimos con la propiedad

font-family: "Sacramento", cursive;

### `Archivo CSS`
Para referenciar un archivo css el cual aportara de estilos nuestra p[agina utilizamos la sentencia

link rel="stylesheet" href="CSS/styles.css"

## **BODY**

### `DIV`

La etiqueta div hace referencia a un contenedor que nos va a permitir dividir el contenido en nuestro sitio web.

[Iconos para el sitio](https://www.flaticon.es/)

### `LISTAS`
La etiqueta `ol` indica una lista ordenada o enumerada, mientras que la etiqueta `ul` indica una lista desordenada o por viñetas, pero una lista no se compone solo de estas etiquetas, también tenemos la etiqueta `li` la cual indica un elemento de estás listas

### `A`

Con la etiqueta a podemos poner hipervinculos dentro de nuestra página con el atributo href y con el atributo target especificamos dónde queremos abrir la página.

### `IMAGE`

La etiqueta image: se divide en dos partes, el elemento HTML (image) y los atributos html (src) que es la ruta o el nombre de la imagen, con las etiquetas width y height determinamos el alto y ancho de la imagen respectivamente para que se adapte a nuestro sitio, si no especificamos las unidades el navegador interpreta estás como pixeles

### `TABLE`

las tablas estan conformadas por filas y columnas las cuales son `tr` para filas y `td` para columnas dentro de las filas. Para la etiqueta table tenemos un atributo llamado `cellspacing` con el cual indicamos el espacio que hay entre las columnas y filas de la tabla

### `FORM`

El atributo `action` indica a donde se debe enviar el formulario, con la propiedad `mailto` en el action del formulario indica que se envie un correo desde el servidor de correo predeterminado del equipo y se declara de la siguiente forma:

action="mailto:nico00540@gmail.com"

El atributo `method` indica el metodo por el cual se va a realizar el envio del formulario bien sea metodo GET o POST

El atributo `enctype` indica el tipo de codificacion del formulario
#### `Ejemplo`
enctype="text/plain" 

En este caso estámos indicando que se enviara un texto sin formato

### `LABEL`
Este elemento determina una etiqueta para reconocer otro elemento

[Generar codigo CSS botones](https://css3buttongenerator.com/)

# PROPIEDADES CSS
## `Margin`
Con esta propiedad definimos las margenes del elemento:
### **Ejemplo**:

**margin: 0;**

Indicamos que el body ocupe todo el contenido de la pagina sin dejar bordes

**margin: 12px;**

Indicamos que el body ocupe el contenido de la página dejando bordes de 12px

Tambien encontramos las siguientes propiedades:

### `margin-top`
Con esta propiedad indicamos las margen unicamente de la parte susperior
### `margin-bottom`
Con esta propiedad indicamos las margen unicamente de la parte inferior
### `margin-left`
Con esta propiedad indicamos las margen unicamente de la parte izquierda
### `margin-right`
Con esta propiedad indicamos las margen unicamente de la parte derecha

O bien podríamos enviar más de un parametro a la propiedad margin y así definir cada margen que queremos:
### **Un parametro**
Se aplicará la misma medida a los cuatro lados
### **Dos parametros**
Se aplicará el primer parametro para la parte de arriba y a bajao y el segundo parametro a la izquierda y derecha
### **Tres parametros**
Se aplicará el primer parametro para la parte de arriba, el segundo para los lados izquierda y derecha y el tercero para la parte de abajo
### **Cuatro parametros**
Se aplicarán a cada lado en sentido de las manecillas del reloj empezando desde arriba (Arriba, Derecha, Aabajo, Izquierda)

## `text-align`
Con este atributo podremos alinear todo el contenido dentro del elemento al cual se le aplique el atributo siempre y cuando este no tenga un ancho definido

## `font-family`
Con este atributo definimos la tipografía que va a utilizar nuestra página

## `font-size`
Con este atributo definimos el tamaño de la letra en nuestra página, este tamaños se puede definir en pixeles, porcentage, em y rem.

En cuanto a tamaño de fuente un 100% es equivalente a 16px por lo que 90px equivaldrían a un 562.5% cuando manejamos % estámos haciendo que sin importar la pantalla el texto sea proporcional a esta.

Así mismo 1 em es equivalente a 16px por lo que 90px equivaldrían a un 5.625em.

Los 1 rem es quivalente a 1 em, estas dos medidas se diferencian en que al declarar el tamaño de la fuente con rem estámos asegurando que al momento de modificar el tamaño de otro texto no va a afectar el tamaño del elemento que hemos modificado.

## `background-color`
Con este atributo podemos definir el color del fondo que le vamos a dar al contenedor o body de nuestra página

## `padding`
Con este atributo podemos definir una margen entre el contenido y el borde de su contenedor

## `height`
Con este atributo definimos el alto del elemento bien sea un contenedor o una imagen

## `width`
Con este atributo definimos el ancho del elemento bien sea un contenedor o una imagen

## `border`
Define el grosor del borde del contenedor

# Propiedades de pantalla CSS
## `Block:`
### **display: block;** 
Ocupa todo el ancho e impide que todo lo demás esten en la misma linea que en ellos, por esto cada elemento se pocisiona en una linea diferente.
## `Inline:` 
### **display: inline;**
Todos los elementos se ponen en una linea, aunque se defina un tamaño para uno de los elementos no lo tomara.
## `Inline-Block:` 
### **display: inline-block;** 
Al igual que la propiedad line tiene el mismo efecto solo que si uno de los elementos tiene un tamaño definido este si lo tomara.

## `None:` 
### **display: none;**
Oculta el elemento y el elemento que sigue ocupara ese lugar

# Posicionamiento relativo y estático: 
Una pagina web HTML por defecto trae posicionamiento estático en cada uno de sus elementos, si queremos desplazar un contenedor debemos utilizar el posicionamiento relativo con el cuál podremos utilizar las siguientes propiedadades:
## `top:` 
desplaza el contenedor desde la parte de arriba. 
## `bottom:` 
Desplaza el contenedor desde la parte de abajo. 
## `rigth:` 
Desplaza el contenedor desde la parte derecha
## `left:` 
Desplaza el contenedor desde la parte izquierda.

Estas propiedades pese a no poder ser implementadas por el posicionamiento estático si que pueden ser implementadas por el posicionamiento absoluto.

# Posicionamiento absoluto: 
Para le posicionamiento absoluto a diferencia del relativo el cual con sus propiedades mueve el contenedor desde su posición por defecto hacía
dónde le indiquemos esta mueve el contenedor hacía donde indiquemos. 
## `Por ejemplo:` 
Si le damos el atributo Right:30px en vez de mover 30 pixeles desde la derecha hacía la izquierda como lo haría el posisicionamiento relativo esta movería el container hacía la derecha dejando 30 píxeles entre el borde derecho de su contenedor y el container al cuál le estamos aplicando dicha propiedad.

# Posicionamiento fijo: 
Con este posicionamiento podremos definir en que parte queremos el container, al momento de desplazar la página este no se moverá ya que tiene un posicionamiento fijo
