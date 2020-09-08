## Paso 8: Añade una lista

En esta solicitud de extracción aprenderás sobre listas y emoji. También enumerarás algunos detalles en tu CV.

:point_down: _¡Estos son diálogos expandibles! Haz clic para abrirlos y ver más información._

<details>
  <summary>Emoji</summary>

  ### Emoji

  Los emoji son divertidos :sparkles:, y pueden ser un poco tontos :stuck_out_tongue_winking_eye:, pero también pueden ser una importante herramienta de comunicación al trabajar con equipos remotos ✅. El tono no se transmite tan claramente cuando leemos texto, si lo comparamos con una conversación cara a cara, y los emojis pueden ser una ayuda a la hora de comunicar contexto y emociones. :heart:

   Los emoji son más apropiados cuando se usan como extras adicionales, no en sustitución del texto. Con las imágenes, el texto descriptivo (alt-text) ayuda a hacerla más accesibles para lectores de pantalla, pero no está garantizado que los lectores de pantalla sepan transmitir la intencionalidad de un emoji. Asegúrate de que tu significado está claro a través del texto, de manera que los emoji resulten de ayuda en lugar de generar más confusión.

  Aquí tienes algunos ejemplos de emoji populares en Markdown.

  | Lo que ves | Lo que escribes |
  | ---------- | ------------ |
  | :heart:    | `:heart:`    |
  | :+1:       | `:+1:`       |
  | :smile:    | `:smile:`    |
  | :sparkles: | `:sparkles:` |
  | :tada:     | `:tada:`     |

  Para más información sobre los emoji disponibles, [revisa esta útil chuleta](https://gist.github.com/rxaviers/7360908). En la mayoría de campos de texto en GitHub, puedes teclear `:` y empezar a escribir el nombre de un emoji. Una búsqueda aproximada te devolverá los cinco mejores resultados y te dejará seleccionar uno.

  ![imagen de búsqueda aproximada de emojis en GitHub](https://user-images.githubusercontent.com/9906718/34602228-47cab148-f1ff-11e7-91f1-56d0fed702f0.png)
  <hr>
</details>


<details>
  <summary>Listas ordenadas</summary>

  ### Listas ordenadas

  Las listas ordenadas tienen números. Puedes anidar listas ordenadas debajo de un elemento de lista añadiendo espacios a su izquierda. Puedes leer más acerca de [formato y sintaxis](https://help.github.com/articles/basic-writing-and-formatting-syntax/) en la _GitHub Help_.

  ```
  1. Item 1
  2. Item 2
  3. Item 3
     1. Item 3a
     2. Item 3b
  ```

  1. Item 1
  2. Item 2
  3. Item 3
     1. Item 3a
     2. Item 3b

 <hr>
</details>

<details>
 <summary>Listas desordenadas</summary>

  ### Listas desordenadas

  Para crear una lista desordenada, usa los caracteres `-` o `*`. Al igual que con las listas ordenadas, puedes anidar una lista añadiendo dos espacios a la izquierda.

  ```
  * Item 1
  * Item 2
    * Item 2a
    * Item 2b
  ```

  * Item 1
  * Item 2
    * Item 2a
    * Item 2b

  <hr>
</details>

### Añadir una lista

Ayuda a que la gente te conozca mejor añadiendo una lista con algunas de tus cosas favoritas. ¿No sabes qué poner? Podrías añadir una lista de tus libros o sitios favoritos donde comer algo.

### :keyboard: Actividad: Crea una lista

{% if preferences.gitTool == 'cli' %}
1. En tu shell, cambia a la rama de esta solicitud de extracción:
      ```shell
      git checkout add-lists-emphasis
      ```
1. En tu editor de textos, abre el archivo `04-lists.md`, en el directorio `_includes`. Crea una lista Markdown en el archivo. Puede ser ordenada o desordenada.
1. Guarda el archivo.
1. Añade tu archivo nuevo como preparado para confirmar:
      ```shell
      git add _includes/04-lists.md
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
1. Edita el archivo `_includes/04-lists.md` en esta solcitud de extracción.
1. Crea una lista Markdown en el archivo. Puede ser ordenada o desordenada.
1. Confirma tus cambios.
{% endif %}

<hr>
<h3 align="center">¡Mira mi respuesta debajo!</h3>
