## Paso 7: Combina tu imagen y tu enlace

¡Tiene muy buen aspecto, @{{ user.username }}! Has creado un enlace para mostrar en tu portafolio, y ahora puedes compartirlo con el mundo.

### :keyboard: Actividad: Combina la solicitud de extracción

{% if preferences.gitTool == 'cli' %}
1. Cámbiate a la rama `master`:
    ```shell
    git checkout master
    ```
2. Combina tu rama:
    ```shell
    git merge add-images-links
    ```
3. Sube tu historial con la rama combinada a GitHub:
    ```shell
    git push
    ```
4. Elimina tu rama local:
    ```shell
    git branch -d add-images-links
    ```
{% else %}
1. Haz clic en **Merge pull request** más abajo.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
