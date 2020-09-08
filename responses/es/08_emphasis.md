## Paso 9: Usa énfasis

¡Buen trabajo con esas listas! Vamos a probar algo nuevo. Puedes usar texto en **negrita** y _cursiva_ en Markdown. Hay un par de formas diferentes para crear énfasis.

```
*Este texto estará en cursiva*
_Este también estará en cursiva_

**Este texto estará en negrita**
__Este también estará en negrita__

_También **puedes** combinarlos_
```

### :keyboard: Actividad: Añade algo de _énfasis_

{% if preferences.gitTool == 'cli' %}
1. En tu shell, asegúrate de que estás en la rama `add-lists-emphasis`:
      ```shell
      git status
      ```
1. Si _no_ lo estás, entonces cámbiate a esa rama:
      ```shell
      git checkout add-lists-emphasis
      ```
1. En tu editor de textos, abre el archivo `05-emphasis.md`, en el directorio `_includes`. Añade alguna información sobre tus habilidades, incluyendo énfasis (como negritas o cursivas).
1. Guarda el archivo.
1. Añade tu archivo nuevo como preparado para confirmar:
      ```shell
      git add _includes/05-emphasis.md
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
1. Edita el archivo `_includes/05-emphasis.md` en esta solicitud de extracción.
1. Utilizando la pestaña **Preview** y tu :sparkles: recién estrenado conocimiento de Markdown, añade énfasis (como negrita o cursiva) a tus capacidades.
1. Introduce un mensaje de confirmación breve y descriptivo.
1. Confirma tus cambios.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
