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
1. In your shell, verify that you are currently checked out to the branch `add-lists-emphasis`:
      ```shell
      git status
      ```
1. If you are _not_, then checkout to that branch:
      ```shell
      git checkout add-lists-emphasis
      ```
1. In your text editor of choice, open the file called `05-emphasis.md`, in the `_includes` directory. Add some information on your skills, including emphasis (like bold or italics).
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/05-emphasis.md
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
1. Edita el archivo `_includes/05-emphasis.md` en esta solicitud de extracción.
1. Utilizando la pestaña **Preview** y tu :sparkles: recién estrenado conocimiento de Markdown , añade énfasis (como negrita o cursiva) a tus capacidades.
1. Introduce un mensaje de confirmación breve y descriptivo.
1. Confirma tus cambios.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
