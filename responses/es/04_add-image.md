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
1. Como hiciste antes, edita el archivo de esta solicitud de extracción.
2. En el archivo, sustituye el contenido de `_includes/02-image.md` con el Markdown correcto para la imagen que hayas elegido. No olvides incluir el alt-text.
3. Confirma tus cambios.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
