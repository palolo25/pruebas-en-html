Apuntes de html






# Introduccion a html

- **Que es HTML**
- HTML significa lenguaje de marcado de hipertexto
- HTML es el lenguaje de marcado estándar para crear páginas web.
- HTML describe la estructura de una página Web
- HTML consta de una serie de elementos
- Los elementos HTML le dicen al navegador cómo mostrar el contenido
- Los elementos HTML etiquetan piezas de contenido como "este es un encabezado", "este es un párrafo", "este es un enlace", etc.




- **Un documento simple de HTML**
``` html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
```
 La <!DOCTYPE html> es una declaracion que define un documento de html5
 
 El <html>elemento es el elemento raíz de una página HTML.
 
 El <head>elemento contiene metainformación sobre la página HTML.
 
 El <title>elemento especifica un título para la página HTML (que se muestra en la 
 barra de título del navegador o en la pestaña de la página)
 
 El <body>elemento define el cuerpo del documento y es un contenedor de todos los contenidos visibles, como encabezados, párrafos, imágenes, hipervínculos, tablas, listas, etc.
 
 El <h1>elemento define un encabezado grande
 
 El <p>elemento define un párrafo.
```

# **Que es un elemnto html**

```
Un elemento HTML se define mediante una etiqueta de inicio, algo de contenido y una etiqueta de finalización:

< nombre de la etiqueta > El contenido va aquí... < /nombre de la etiqueta >
El elemento HTML es todo, desde la etiqueta de inicio hasta la etiqueta final:

< h1 > Mi primer encabezado < /h1 >
< p > Mi primer párrafo. < /p >
```
- # Etiquetas html


- Encabezados 

HTML incluye 6 niveles de encabezados desde el h1 el mas grande al h6 el mas pequeño.
```HTML
<html>
    <head>
        <title>Primera pagina</title>
    </head>
    <body>
        <h1>este es el encabezado</h1>
        <h2>este es el encabezado</h2>
        <h3>este es el encabezado</h3>
        <h4>este es el encabezado</h4>
        <h5>este es el encabezado</h5>
        <h6>este es el encabezado</h6>
    </body>
</html>
```
- lineas horizontales
```HTML
<hr>

```

- comentarios

Para escribir comentarios hay que hacer lo siguiente.

```HTML
<!-- ESTO ES UN COMENTARIO -->
```
### **Parrafos html**

Los parrafos se definen con la etiqueta ```<p>```.
```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
### **Enlaces html**
Los enlaces html se definen con la etiqueta ```<a>```.
```html
<a href="https://www.w3schools.com">This is a link</a>
```

### **Imagenes html**
Las imagenes html se definen con la etiqueta ```<img>```.
El archivo de origen ( src), el texto alternativo ( alt), widthy heightse proporcionan como atributos.

```html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```

# **Elementos html**
El elemento html es todo desde la etiqueta de inicio hasta la etiqueta del final, segun el tipo de etiqueta le va ha hacer falta un final o no, las podemos clsificar como etiquetas abiertas que son las que no tienen un final y las cerradas que tienen un inicio y un final.

- Abiertas
```<hr>```
- Cerradas 
```< h1 > Mi primer encabezado < /h1 >```

## **Elementos anidados**

Los elementos de html se pueden anidar, esto significa que una etiqueta puede contener otra etiqueta. Todos los elementos html constan de elementos html anidados.
```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

# **Atributos**

- Todos los elementos HTML pueden tener atributos
- Los atributos proporcionan información adicional sobre los elementos .
- Los atributos siempre se especifican en la etiqueta de inicio
- Los atributos generalmente vienen en pares de nombre/valor como: nombre="valor"

## El atributo href

La ```<a>``` define un hipervinculo y href especifica la URL a la que v el enlace. Los hipervínculos también son una parte fundamental de cualquier página web. Puede agregar hipervínculos a textos o imágenes que le permitirán al usuario hacer click en ellos para luego ser redirigidos a otro archivo o página web.

```html
<a href="https://www.w3schools.com">Visit W3Schools</a>
```
## El atributo target

Este atributo especfica donde se abre el documento vinculado.

```html
<a href= "vinculo" target="_blank">hola mundo</a>
```
## El atributo src 
la ```<img>``` es una etiqueta utilizada par incrustar una imagen en una pagina html. El src es un atributo que especifica la ruta a la imaagen que se va a mostrar

```html
<img src="img_girl.jpg">
```
Hay dos formas de especificar la Url en el src atributo:
1. 1. URL absoluta : enlaces a una imagen externa alojada en otro sitio web. Ejemplo: src="https://www.w3schocols.com/images/img_girl.jpg" .


1. URL relativa : enlaces a una imagen alojada en el sitio web. Aquí, la URL no incluye el nombre de dominio. Si la URL comienza sin una barra inclinada, será relativa a la página actual. Ejemplo: src="img_girl.jpg". Si la URL comienza con una barra inclinada, será relativa al dominio. Ejemplo: src="/images/img_girl.jpg".


## Atributos de ancho y alto

La ```<img>``` de contener las etiquetas de width y height que especifican el ancho y el alto de la imagen (en pixeles).

```html
<img src="img_girl.jpg" width="500" height="600">
```

## El atributo de alt
El alt requerido para la ```<img>```  etiqueta especifica un texto alternativo para una imagen, si la imagen por algún motivo no se puede mostrar. Esto puede deberse a una conexión lenta, a un error en el src atributo, o si el usuario usa un lector de pantalla.

```html
<img src="img_girl.jpg" alt="Girl with a jacket">
```

## Atributo style

El style es un atributo que se usa para agregar estilos a un elemento como colo, fuente, tamaño y mas.

```html
<p style="color:red;">This is a red paragraph.</p>
```


## Atributo lang

El atributo lang va dentro de la etiqueta html para declarar el idioma de la pagina, esto sirve para ayudar a los motores de busqueda y a los navegadores.

```html
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```
## Atributo title

El atributo title define informacion adicional sobre un elemento, su valor se mostrara como informacion sobre herramientas cuando pase el mouse sobre el elemento.

```html
<p title="I'm a tooltip">This is a paragraph.</p>
```
# **Formularios**
Los formularios HTML son usados para recolectar información del usuario.
Los formularios son definidos usando el elemento ```<form>``` , con sus etiquetas de apertura y cierre.ç
```html
<body>

    <form></form>

</body>
```

## Atributo action

Este atributo ```<action>``` nos permite apuntar a una pagina web que cargara despues de que el usuario envie el formulario.

## Atributos method y name

El atributo method especifica el método HTTP (GET o POST) a ser usado cuando los formularios son enviados (observe abajo la descripción)

```html
<form action="url" method="GET">

<form action="url" method="POST">
```
Cuando usamos GET, los datos del formulario serán visibles en la dirección de la página.
Utiliza POST si el formulario está actualizando datos, o incluye información sensible (contraseñas).  POST ofrece mejor seguridad porque los datos enviados no son visibles en la dirección de la página.

## Atributo input

El elemento ```<input>``` tiene muchas variaciones, dependiendo del tipo de atributo.  Puede ser texto, contraseña, radio, URL, envío, etc.

```html
<form>
    <input type="text" name="usuario"/><br />
    <input type="password" name="contraseña"/>
</form>
```
### Elementos de formularios

Si cambiamos el tipo ```<input>``` a ```<radio>```, permitiremos al usuario seleccionar sólo una de un número de opciones desplegadas.

```html
<input type="radio" name="gender" value="male" />Masculino<br />
<input type="radio" name="gender" value="female" />Femenino<br />
```
El tipo "checkbox" permite al usuario seleccionar más de una opción.
```html
<input type="checkbox" name="gender" value="1" />Masculino<br />
<input type="checkbox" name="gender" value="2" />Femenino<br />
```
El tipo ```submit``` envía un formulario a la dirección especificada en su atributo action.
```html
<input type="submit" value="enviar" />
```


# **Tipos de elementos**
