Algo no pinta bien con ese enlace. Asegúrate de que:

- Has eliminado el texto de relleno
- El formato de tu enlace es el correcto (`[texto](url)`)

### :keyboard: Actividad: Añade un enlace

{% if preferences.gitTool == 'cli' %}
1. In your shell, verify that you are currently checked out to the branch `add-images-links`:
      ```shell
      git status
      ```
1. If you are _not_, then checkout to that branch:
      ```shell
      git checkout add-images-links
      ```
1. In your text editor of choice, open the file called `03-links.md`, in the `_includes` directory. Add a link using the syntax `[text](https://example.com)`.
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/03-links.md
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
1. Haz scroll para localizar el archivo `_includes/03-link.md`.
1. Haz clic en el icono del :pencil: lápiz.
1. Añade un enlace utilizando la sintaxis `[texto](https://example.com)`.
1. Haz scroll a la parte inferior y confirma los cambios a tu rama.
{% endif %}

Si necesitas ayuda para resolver algún problema, crea un post en el tablón de [GitHub Community]({{ communityBoard }}). Puede que también quieras realizar una búsqueda para ver si alguien ha resuelto algún problema como el tuyo en el pasado.

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
