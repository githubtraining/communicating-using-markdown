Algo no pinta bien con ese enlace. Asegúrate de que:

- Has eliminado el texto de relleno
- El formato de tu enlace es el correcto (`[texto](url)`)

### :keyboard: Actividad: Añade un enlace

{% if preferences.gitTool == 'cli' %}
1. En tu shell, asegúrate de que estás en la rama `add-images-links`:
      ```shell
      git status
      ```
1. Si _no_ lo estás, entonces cámbiate a esa rama:
      ```shell
      git checkout add-images-links
      ```
1. En tu editor de textos, abre el archivo `03-links.md`, en el directorio `_includes`. Añade un enlace usando la sintaxis `[texto](https://example.com)`.
1. Guarda el archivo.
1. Añade tu archivo nuevo como preparado para confirmar:
      ```shell
      git add _includes/03-links.md
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
1. Haz scroll para localizar el archivo `_includes/03-link.md`.
1. Haz clic en el icono del :pencil: lápiz.
1. Añade un enlace utilizando la sintaxis `[texto](https://example.com)`.
1. Haz scroll a la parte inferior y confirma los cambios a tu rama.
{% endif %}

Si necesitas ayuda para resolver algún problema, crea un post en el tablón de [GitHub Community]({{ communityBoard }}). Puede que también quieras realizar una búsqueda para ver si alguien ha resuelto algún problema como el tuyo anteriormente.

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
