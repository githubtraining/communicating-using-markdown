## Paso 10: Combina las listas y los énfasis

¡Una lista genial, @{{ user.username }}! Puedes combinar la solicitud de extracción cuando hayas terminado.

### :keyboard: Actividad: Combina la solicitud de extracción

{% if preferences.gitTool == 'cli' %}
1. Cámbiate a la rama `master`:
    ```shell
    git checkout master
    ```
2. Combina tu rama:
    ```shell
    git merge add-lists-emphasis
    ```
3. Sube tu historial con la rama combinada a GitHub:
    ```shell
    git push
    ```
4. Elimina tu rama local:
    ```shell
    git branch -d add-lists-emphasis
    ```
{% else %}
1. Haz clic en **Merge pull request** más abajo.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
