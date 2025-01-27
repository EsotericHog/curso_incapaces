# Módulo 1 - Sección 8: Formularios

## ¿Qué son los formularios?
Los formularios en HTML son estructuras creadas con la etiqueta `<form>` que permiten recolectar datos del usuario a través de campos como `<input>`, `<textarea>`, `<select>` y botones, para enviarlos a un servidor para su procesamiento.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formularios</title>
</head>
<body>
    <!--Formulario simplificado-->
    <form>
        <!--Campos del formulario-->
        <input type="text">
        <input type="email">
        <input type="password">
        <input type="checkbox">
        <input type="radio">
        <input type="submit">
    </form>
    
</body>
</html>
```
Todos los inputs dentro del elemento `<form>` formarán parte del formulario de forma automática. Y se enviarán por defecto a la ruta que será indicada en el atributo `action`. Si éste está vacío, significa que el formulario se enviará a la msma página actual. También se puede especificar el método de envío usando el atributo `method`.

## Elemento Input
El elemento más común es el `<input>`. Tenemos varios tipos de input. Los más comunes son los siguientes:
- `text` : El más común. Utilizado para ingresar texto (cualquier caracter ingresado será parte de una cadena de texto)
- `email` : Similar al anterior. Antes de enviar el formulario, éste elemento verifica que su contenido tenga el formato email.
- `password` : Input utilizado para las contraseñas. Oculta los caracteres escritos por el usuario y los reemplaza por asteriscos.
- `checkbox` : Casilla para marcar múltiples opciones a la vez
- `radio` : Casilla para marcar una opción única dentro de un mismo grupo
- `submit` : Input que funciona como un botón que envía el formulario