Has realizado algún cambio a este archivo, pero no veo ningún encabezado. Añade otra confirmación de cambios (o _commit_) con un encabezado en el archivo. Puedes seguir añadiendo y confirmando cambios en una rama incluso después de iniciar una solicitud de extracción.

### :keyboard: Actividad: Añade un encabezado

{% if preferences.gitTool == 'cli' %}
1. Open your preferred command line interface, which we'll call your shell from now on.
1. Clone this repository:
      ```shell
      git clone {{ thePayload.repository.clone_url }}
      ```
1. Navigate to the repository in your shell:
      ```shell
      cd {{ thePayload.repository.name }}
      ```
1. Checkout to the branch in this pull request:
      ```shell
      git checkout add-headers
      ```
1. In your text editor of choice, open the file called `01-name.md`, in the `_includes` directory. On the first line, replace the text with your name, and add a `#` before the content to make it an H1 Header.
1. Save your file.
1. Stage your file:
      ```shell
      git add _includes/01-name.md
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
1. Haz scroll para buscar el archivo `_includes/01-name.md`.
1. Haz clic en el icono del :pencil: lápiz.
1. Añade un encabezado tecleando `#` seguido de un espacio.
1. Haz scroll a la parte inferior y confirma tus cambios en la rama.
{% endif %}

Si necesitas ayuda para resolver algún problema, crea un post en el tablón de [GitHub Community]({{ communityBoard }}). Puede que también quieras realizar una búsqueda para ver si alguien ha resuelto algún problema como el tuyo en el pasado.

<hr>
<h3 align="center">¡Mira debajo para ver mi respuesta!</h3>
