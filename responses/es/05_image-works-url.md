## Paso 6: Añade un enlace de perfil

¡Tu imagen tiene muy buen aspecto! Ahora querrás añadir enlaces a los impresionantes proyectos de tu portafolio. Los enlaces ayudan a crear contexto cuando te comunicas en las propuestas (o _issues_) y solicitudes de extracción (o _pull requests_).

Puedes enlazar un [sitio web](https://github.com/), un [repositorio](https://github.com/github/training-kit), o incluso una [línea de código](https://github.com/github/training-kit/blob/master/resources/learning-path/index.html#L32). Para crear un enlace, coloca el texto que quieres mostrar entre corchetes, y la URL a continuación entre paréntesis.

```
[GitHub](http://github.com)
```

## :keyboard: Actividad: Añade un enlace

{% if preferences.gitTool == 'cli' %}
1. En tu shell, asegúrate de que estás en la rama `add-images-links`:
      ```shell
      git status
      ```
1. Si _no_ lo estás, entonces cámbiate a esa rama:
      ```shell
      git checkout add-images-links
      ```
1. En tu editor de textos, abre el archivo `03-links.md`, en el directorio `_includes`. Sustituye el texto de relleno con un enlace a tu perfil en GitHub (o a cualquier otro sitio).
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
1. Edita el archivo `_includes/03-links.md`.
1. Sustituye el texto de relleno con un enlace a tu perfil de GitHub (o a cualquier otro sitio.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
