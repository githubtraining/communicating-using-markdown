Algo no está del todo bien con esa imagen. Asegúrate de que:

- Has eliminado el texto de relleno
- El formato de tu imagen es el correcto (`![alt-text](url-de-la-imagen)`)
- La imagen tiene texto alternativo (alt-text)

### :keyboard: Actividad: Añade una imagen

{% if preferences.gitTool == 'cli' %}
1. In your shell, checkout to the branch in this pull request:
      ```shell
      git checkout add-images-links
      ```
1. In your text editor of choice, open the file called `02-image.md`, in the `_includes` directory. In the file, replace the content with the correct Markdown for your image of choice. Don't forget to include alt-text!
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/02-image.md
      ```
1. Commit the change and add a commit message:
      ```shell
      git commit -m "<YOUR MESSAGE>"
      ```
1. Push your new commit to GitHub:
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

Si necesitas ayuda para resolver algún problema, crea un post en el tablón de [GitHub Community]({{ communityBoard }}). Puede que también quieras realizar una búsqueda para ver si alguien ha resuelto algún problema como el tuyo en el pasado.

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
