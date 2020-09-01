## Paso 5: Añade una imagen

Ahora vas a añadir una imagen. Puedes añadir una imagen tuya o cualquier cosa que te gustaría mostrar en tu portafolio. También aprenderás a crear texto descriptivo, o "alt text", a las imágenes, y a crear enlaces.

### Imágenes
Vamos a añadir una imagen. No olvides incluir un texto descriptivo entre los corchetes. Este texto se lee en voz alta para las personas que utilizan lectores de pantalla. A veces también puede mostrarse cuando no es posible recuperar la imagen, como cuando hay problemas de conexión. Puedes ver la sintaxis para añadir imágenes aquí:

```
![Imagen del Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

![Imagen del Yaktocat](https://octodex.github.com/images/yaktocat.png)

### :keyboard: Actividad: Añadir una imagen

{% if preferences.gitTool == 'cli' %}
1. En tu shell, cambia a la rama de esta solicitud de extracción:
      ```shell
      git checkout add-images-links
      ```
1. En tu editor de textos, abre el archivo `02-image.md`, en el directorio `_includes`. En el archivo, sustituye el contenido con el Markdown correcto para la imagen que has elegido. No te olvides de incluir texto alternativo.
1. Guarda el archivo.
1. Añade tu archivo nuevo como preparado para confirmar:
      ```shell
      git add _includes/02-image.md
      ```
1. Confirma el cambio y añade un mensaje de confirmación:
      ```shell
      git commit -m "<TU MENSAJE>"
      ```
1. Sube tus nuevos cambios confirmados a GitHub:
      ```shell
      git push
      ```
{% else %}
1. Como hiciste antes, edita el archivo de esta solicitud de extracción.
2. En el archivo, sustituye el contenido de `_includes/02-image.md` con el Markdown correcto para la imagen que hayas elegido. No olvides incluir el alt-text.
3. Confirma tus cambios.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
