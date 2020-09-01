## Paso 7: Combina tu imagen y tu enlace

¡Tiene muy buen aspecto, @{{ user.username }}! Has creado un enlace para mostrar en tu portafolio, y ahora puedes compartirlo con el mundo.

### :keyboard: Actividad: Combina la solicitud de extracción

{% if preferences.gitTool == 'cli' %}
1. Check out to the `master` branch:
    ```shell
    git checkout master
    ```
2. Merge your branch:
    ```shell
    git merge add-images-links
    ```
3. Push the merged history to GitHub:
    ```shell
    git push
    ```
4. Delete your the branch locally:
    ```shell
    git branch -d add-images-links
    ```
{% else %}
1. Haz clic en **Merge pull request** más abajo.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
