Has realizado algún cambio a este archivo, pero no veo ningún encabezado. Añade otra confirmación de cambios (o _commit_) con un encabezado en el archivo. Puedes seguir añadiendo y confirmando cambios en una rama incluso después de iniciar una solicitud de extracción.

### :keyboard: Actividad: Añade un encabezado

{% if preferences.gitTool == 'cli' %}
1. Abre tu interfaz de línea de comandos favorita, a la que llamaremos shell a partir de ahora.
1. Clona este repositorio:
      ```shell
      git clone {{ thePayload.repository.clone_url }}
      ```
1. Navega al repositorio en tu shell:
      ```shell
      cd {{ thePayload.repository.name }}
      ```
1. Cambia a la rama de esta solicitud de extracción:
      ```shell
      git checkout add-headers
      ```
1. En tu editor de textos, abre el archivo `01-name.md`, en el directorio `_includes`. En la priemra línea, sustituye el texto con tu nombre y añade una `#` antes del contenido para convertirlo en un encabezado H1.
1. Guarda el archivo.
1. Añade el archivo como preparado para confirmar:
      ```shell
      git add _includes/01-name.md
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
1. Haz clic en la pestaña "Files changed".
1. Haz scroll para buscar el archivo `_includes/01-name.md`.
1. Haz clic en el icono del :pencil: lápiz.
1. Añade un encabezado tecleando `#` seguido de un espacio.
1. Haz scroll a la parte inferior y confirma tus cambios en la rama.
{% endif %}

Si necesitas ayuda para resolver algún problema, crea un post en el tablón de [GitHub Community]({{ communityBoard }}). Puede que también quieras realizar una búsqueda para ver si alguien ha resuelto algún problema como el tuyo anteriormente.

<hr>
<h3 align="center">¡Mira debajo para ver mi respuesta!</h3>
