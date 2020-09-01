## Paso 6: Añade un enlace de perfil

¡Tu imagen tiene muy buen aspecto! Ahora querrás añadir enlaces a los impresionantes proyectos de tu portafolio. Los enlaces ayudan a crear contexto cuando te comunicas en las propuestas (o _issues_) y solicitudes de extracción (o _pull requests_).

Puedes enlazar un [sitio web](https://github.com/), un [repositorio](https://github.com/github/training-kit), o incluso una [línea de código](https://github.com/github/training-kit/blob/master/resources/learning-path/index.html#L32). Para crear un enlace, coloca el texto que quieres mostrar entre corchetes, y la URL a continuación entre paréntesis.

```
[GitHub](http://github.com)
```

## :keyboard: Actividad: Añade un enlace

{% if preferences.gitTool == 'cli' %}
1. In your shell, verify that you are currently checked out to the branch `add-images-links`:
      ```shell
      git status
      ```
1. If you are _not_, then checkout to that branch:
      ```shell
      git checkout add-images-links
      ```
1. In your text editor of choice, open the file called `03-links.md`, in the `_includes` directory. Replace the filler text with a link to your GitHub profile (or anywhere else).
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
1. Edita el archivo `_includes/03-links.md`.
1. Sustituye el texto de relleno con un enlace a tu perfil de GitHub (o a cualquier otro sitio.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
