# introducción a HTML y CSS

Todos los sitios web están escritos en HTML y CSS

## HTML

HTML es un lenguaje de **marcado**, es decir, le da la estructura la sitio web

HTML o `Hypertest Markap Language` hace que el contenido de páginas web tenga una estructura lógica y semántica

–---

### Estructura básica de un doc HTML
estructura básica del sitio web que tiene el encabezado "Mi sitio web" y un párrafo que dice "Bienvenidos a mi sitio web"

para hacer esto se necesitan etiquetas para **marcar** el contenido

las etiquetas **html**, <head>, y <body> se utilizan para marcar el inicio y el final de la pagina web, por otra parte, las etiquetas <title>, <h1> y <p>, se utilizan para **marcar** el contenido de la página. El encabezado es <h1> yel párrafo es <p>.

2 secciones importantes don *la cabecera* de la pagina q corresponde a <head> y el *cuerpo* q corresponde a <body>: las secciones pueden tener subsecciones.

otra etiqueta importante <!DOCTYPE>: esta define el tipo de documento y le permite al navegador web interpretar correctamente el código **html**

* Example
```html
<!DOCTYPE html>
<html>
<head>
	<title>Mi sitio web</title>
</head>
<body>
	<h1>Mi sitio web</h1>
	<p>Biembenido a mi sitio web</p>
</body>
</html>
```

Etiqueta <!DOCTYPE>

HTML, como todos los lenguajes, ha pasado por diferentes versiones con el pasar del tiempo y su implementación. Por esto mismo, es necesario indicar al navegador la versión de HTML en la que se encuentran escritos los documentos que estamos intentando renderizar (mostrar en la pantalla del navegador).

Para ello, existe la etiqueta <!DOCTYPE> que, como su nombre lo indica, define el tipo de documento e indica al navegador cómo debe interpretar el código HTML. Para el objetivo de nuestro curso sólo usaremos la etiqueta que define el tipo de documento como HTML5. La definimos de la siguiente manera:

 <!DOCTYPE>



#### Estructura básica de un documento HTML5

Para definir que el documento creado es un documento con la versión 5 de HTML se debe incluir la etiqueta <!DOCTYPE> antes de la etiqueta de apertura <html>

```html
<!DOCTYPE html>
<html>
	<head>

	</head>

	<body>
	</body>
</html>
```



#### Estructura de una etiqueta

Una etiqueta es una marca o identificador que se utiliza para definir el inicio y el final de un elemento dentro de una página web. 

Cada etiqueta se compone de corchetes angulares (< y >), seguidos del nombre de la etiqueta, y puede tener **atributos** y **valores** que proporcionan información adicional sobre el elemento. Las etiquetas se utilizan para definir la estructura y el contenido de una página web, y permiten al navegador interpretar y renderizar correctamente la información que se muestra al usuario. Ejemplos de etiquetas en HTML incluyen <html>, <head>, <body>, <p>, <img>, <a>, entre otras.

Podemos referirnos a las etiquetas como elementos, sin embargo hay una pequeña diferencia entre estos conceptos:

Elemento: Es el bloque de HTML que ya ha sido renderizado, generalmente está conformado por dos etiquetas separadas, una de apertura y otra de cierre.

Etiqueta: La etiqueta está escrita de una forma que el navegador pueda encontrarla, rodeada de los símbolos menor que < y mayor que >.

#### Etiquetas de maquetado

Etiquetas de textos y formatos
Etiqueta imagen
Tablas
Listas
Enlaces
Elementos en bloque y en línea
Formularios (tipos de inputs, funcionamiento)

## CSS
CSS es un lenguaje de **estilos** y **apariencia** y se utiliza para cambiar la apariencia de un citio web, así pues, se fuede cambiar la forma, se le puede dar color, el tamaños de los elementos, es como la piel de la pagina web


Formas de implementar CSS
Selectores, herencia y cascada, prioridades
Estilos de texto
Estilos de fondo
Pseudo-classes
Estilos de imágenes 
Display y Box Modeling
Flexbox
Grids


