# Módulo 1 - Sección 3: Estructura de una etiqueta

## Archivo HTML
La extensión del archivo HTML es `.html`

## Contenido de documento HTML
Todo en HTML funciona con etiquetas. Para crear una etiqueta, se debe usar los símbolos menor que y mayor que, de esta forma: `<etiqueta>`. Hay etiquetas que requieren una **apertura** y un **cierre**. El cierre es lo mismo que la apertura, sólo que se le agrega una barra diagonal (`/`) después del primer símbolo. A continuación, un ejemplo:

```html
<!--Elemento HTML representado mediante etiqueta-->
<nombre></nombre>
```
"nombre" representa el nombre de la etiqueta.

HTML incluye etiquetas con nombres y propiedades preestablecidas. Sin embargo, también podemos inventar nuestras propias etiquetas.

```html
<tag>           <!--Apertura de etiqueta-->
    CONTENIDO   <!--Contenido de la etiqueta-->
</tag>          <!--Cierre de etiqueta-->
```
El contenido de una etiqueta puede ser texto o incluso otra etiqueta.

## Estructura básica de un documento HTML
Crea un archivo HTML y usando VSCode escribe `html:5` y da `Enter`. Obtendrás la estructura básica de html.
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

- `<!DOCTYPE html>` : Define la versión de HTML que estamos usando. En este caso es la última. Esta etiqueta no necesita cerrarse.
- `<html></html>` : Define lo que va a formar parte de la página web
- `<head></head>` : Provee información general (metadatos) acerca del documento, incluyendo su título y enlaces a scripts y hojas de estilos. Todo lo que esté contenido aquí no es visible.
- `<meta>` : Define metadatos.
- `<title></title>` : Define el título de la página. Visible en la pestaña del navegador.
- `<body></body>` : Define todo lo visible de la web

Fuente: [Soy Dalto: Curso de HTML y CSS desde CERO (Completo)](https://www.youtube.com/watch?v=ELSm-G201Ls&t=1962s&ab_channel=SoyDalto)