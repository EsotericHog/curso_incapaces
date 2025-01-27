# Módulo 1 - Sección 7: Imágenes, audio y videos

## Cargar imágenes
Usa la etiqueta `<img>` para incluir imágenes en el documento. Para asignarle un enlace a la imagen, debemos definir el valor de su atributo `src` asignándole una cadena de texto entre comillas con el enlace.
```html
<img src="https://cdn.wamiz.fr/cdn-cgi/image/format=auto,quality=80,width=1200,height=900,fit=cover/article/main-picture/60479ae773a23365656927.jpg" alt="Imagen de gato persa">
```
el atributo `alt` se usa para definir una descripción de la imagen en caso de que ésta no pueda ser visualizada.


## Cargar video
Usa la etiqueta `<video>` para incluir videos e incluye la ruta en el atributo `src`. Puedes incluir el atributo `autoplay` para reproducir el video automáticamente, `controls` para mostrar los controles del reproductor, y `muted` para que el video inicie en silencio.
```html
<video controls autoplay muted src="video.mp4"></video>
```
Es posible incluir subtítulos o captions para el video usando `<track>`:
```html
<video controls autoplay muted src="video.mp4">
    <track src="subtitles.vtt" default kind="subtitles" srclang="es">
    <track src="captions.vtt" default kind="captions" srclang="es">
</video>
```


## Cargar audio
Usa la etiqueta `<audio>` para incluir videos e incluye la ruta en el atributo `src`.
```html
<audio controls autoplay muted src="canciondefondo.mp3"></audio>
```