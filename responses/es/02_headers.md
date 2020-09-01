## Paso 3: Añade encabezados

Como has podido ver en tu sitio web, tu portafolio no tiene mucho contenido todavía. Aprenderemos a editar un archivo en esta solicitud de extracción para incorporar algunos encabezados en Markdown.

Puedes ver un ejemplo de encabezado en la parte superior de esta página. Exactamente igual que como en HTML, un encabezado es un fragmento de texto un poco más grande al principio de una sección. Hay seis tamaños.

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
1. Open your preferred command line interface, which we'll call your shell from now on.
1. Clone this repository:
      ```shell
      git clone {{ thePayload.repository.clone_url }}
      ```
1. Navigate to the repository in your shell:
      ```shell
      cd {{ thePayload.repository.name }}
      ```
1. Checkout to the branch in this pull request:
      ```shell
      git checkout add-headers
      ```
1. In your text editor of choice, open the file called `01-name.md`, in the `_includes` directory. On the first line, replace the text with your name, and add a `#` before the content to make it an H1 Header.
1. Save your file. Every time you make changes, it's a good idea to type `git status`. You should type this after you stage files, and after you commit. It's always a good idea!
1. Stage your file:
      ```shell
      git add _includes/01-name.md
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
1. En esta solicitud de extracción, haz clic en la pestaña **Files changed**.
1. En el extremo superior derecho de la vista de archivo, haz clic en el icono de **lápiz** ✏️ del archivo titulado `_includes/01-name.md`.
1. En la pestaña **Edit file**, añade una `#` antes del contenido para convertirlo en un encabezado H1. Puedes añadir más encabezados, usando entre uno y seis caracteres `#`.
1. Encima de tu nuevo contenido, haz clic en **Preview changes**.
1. En la parte inferior de la página, escribe un mensaje de confirmación breve y significativo que describa el cambio que has realizado en el archivo.
1. Haz clic en **Commit changes**.
{% endif %}

<hr>
<h3 align="center">Mira mi respuesta aquí debajo.</h3>
