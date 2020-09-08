Algo no está del todo bien con esa imagen. Asegúrate de que:

- Has eliminado el texto de relleno
- El formato de tu imagen es el correcto (`![alt-text](url-de-la-imagen)`)
- La imagen tiene texto alternativo (alt-text)

### :keyboard: Actividad: Añade una imagen

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
1. Haz clic en la pestaña "Files changed".
1. Haz scroll para localizar el archivo `_includes/02-image.md`.
1. Haz clic en el icono del :pencil: lápiz.
1. Añade una imagen usando la sintaxis `![Imagen del Yaktocat](https://octodex.github.com/images/yaktocat.png)`.
1. Haz scroll a la parte inferior y confirma los cambios a tu rama.
{% endif %}

Si necesitas ayuda para resolver algún problema, crea un post en el tablón de [GitHub Community]({{ communityBoard }}). Puede que también quieras realizar una búsqueda para ver si alguien ha resuelto algún problema como el tuyo anteriormente.

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
