Oh oh, no podemos encontrar tu lista.

Recuerda que el formato de una lista tiene este aspecto:

`- item`

Es importante poner un espacio entre el `-` o `*` y el texto del elemento de lista.

### :keyboard: Actividad: Añade una lista

{% if preferences.gitTool == 'cli' %}
1. En tu shell, cambia a la rama de esta solicitud de extracción:
      ```shell
      git checkout add-lists-emphasis
      ```
1. En tu editor de textos, abre el archivo `04-lists.md`, en el directorio `_includes`. Crea una lista Markdown en el archivo. Puede ser ordenada o desordenada. Usa `-` o `*` para indicar los elementos de la lista.
1. Guarda el archivo.
1. Añade tu archivo nuevo como preparado para confirmar:
      ```shell
      git add _includes/04-lists.md
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
1. Haz scroll para localizar el archivo `_includes/04-lists.md`.
1. Haz clic en el icono del :pencil: lápiz.
1. Añade una lista usando `-` o `*` para indicar los elementos de la lista.
1. Haz scroll a la parte inferior y confirma los cambios a tu rama.
{% endif %}

Si necesitas ayuda para resolver algún problema, crea un post en el tablón de [GitHub Community]({{ communityBoard }}). Puede que también quieras realizar una búsqueda para ver si alguien ha resuelto algún problema como el tuyo anteriormente.

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
