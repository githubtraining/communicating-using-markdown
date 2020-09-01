## Paso 4: Combina tus encabezados

Veo que has añadido al menos un encabezado, @{{ user.username }}. Puedes continuar trabajando si quieres; de lo contrario, vamos a combinar (o _merge_) <sup>[:book:](https://help.github.com/articles/github-glossary/#merge)</sup> esta solicitud de extracción para continuar con el curso.

### :keyboard: Actividad: Combina la solicitud de extracción

{% if preferences.gitTool == 'cli' %}
1. Check out to the `master` branch:
    ```shell
    git checkout master
    ```
2. Merge your branch:
    ```shell
    git merge add-headers
    ```
3. Push the merged history to GitHub:
    ```shell
    git push
    ```
4. Delete your the branch locally:
    ```shell
    git branch -d add-headers
    ```
{% else %}
1. Haz clic en **Merge pull request** más abajo.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta aquí debajo!</h3>
