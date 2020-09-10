## Paso 3: Añade encabezados

Como has podido ver en tu sitio web, tu portafolio no tiene mucho contenido todavía. Aprenderemos a editar un archivo en esta solicitud de extracción para incorporar algunos encabezados en Markdown.

Puedes ver un ejemplo de encabezado en la parte superior de esta página. Exactamente igual que en HTML, un encabezado es un fragmento de texto un poco más grande al principio de una sección. Hay seis tamaños.

#### Ejemplo

```
# Esto es un encabezado <h1>, que es el más grande
## Esto es un encabezado <h2>
###### Esto es un encabezado <h6>, que es el más pequeño
```

#### Cómo se muestra

# Esto es un encabezado <h1>, que es el más grande
## Esto es un encabezado <h2>
###### Esto es un encabezado <h6>, que es el más pequeño

En propuestas (o _issues_), solicitudes de extracción (o _pull requests_) y comentarios puedes usar la barra de herramientas de formato.

La barra de herramientas no está disponible en todas partes. Cuando editas un archivo, tienes que teclear los caracteres `#` manualmente.

### :keyboard: Actividad: Edita tu archivo con encabezados

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
1. En tu editor de textos, abre el archivo `01-name.md`, en el directorio `_includes`. En la primera línea, sustituye el texto con tu nombre y añade una `#` antes del contenido para convertirlo en un encabezado H1.
1. Guarda el archivo. Cada vez que hagas algún cambio, es buena idea teclear `git status`. Deberías hacer esto después de que añadas archivos como preparados para confirmar, y después de confirmar cambios. 
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
1. En esta solicitud de extracción, haz clic en la pestaña **Files changed**.
1. En el extremo superior derecho de la vista de archivo, haz clic en el icono de **lápiz** ✏️ del archivo titulado `_includes/01-name.md`.
1. En la pestaña **Edit file**, añade una `#` antes del contenido para convertirlo en un encabezado H1. Puedes añadir más encabezados, usando entre uno y seis caracteres `#`.
1. Encima de tu nuevo contenido, haz clic en **Preview changes**.
1. En la parte inferior de la página, escribe un mensaje de confirmación breve y significativo que describa el cambio que has realizado en el archivo.
1. Haz clic en **Commit changes**.
{% endif %}

<hr>
<h3 align="center">Mira mi respuesta aquí debajo.</h3>
