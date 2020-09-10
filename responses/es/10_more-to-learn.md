## Buen trabajo

Enhorabuena @{{ user.username }}, ¡has completado este curso!

![enhorabuena](https://octodex.github.com/images/welcometocat.png)

## Lo que ha ido bien

En este curso has conseguido:

- Añadir una lista de tareas a un comentario en una propuesta
- Activar GitHub Pages en tu repositorio
- Confirmar cambios a tu sitio web, en concreto:
    - Añadiste encabezados al archivo `01-name.md`
    - Insertaste una imagen en el archivo `02-image.md` 
    - Creaste enlaces a otros sitios web en el archivo `03-links.md` 
    - Añadiste una lista de tus logros en el archivo `04-lists.md` 
    - Usaste énfasis como **negrita** y _cursiva_ en el archivo `05-emphasis.md` 

## ¿Y ahora, qué?

Ahora que ya dominas los aspectos básicos de Markdown, @{{ user.username }}, aquí tienes alguna información rápida acerca de otras funcionalidades interesantes que no hemos visto hasta ahora.

### Más enlaces en Markdown

<details>
<summary>@menciones de Usuarios y Equipos</summary>

  ### @menciones de Usuarios y Equipos

  Si tecleas el símbolo `@` seguido de un nombre de usuario de GitHub, se enviará una notificación a esa persona para informarle acerca de tu comentario. Esto se llama una "@mencion", porque estás mencionando a otra persona. También puedes `@mencionar` equipos dentro de una misma organización. Para más información, puedes consultar “[Receiving notifications about activity on GitHub](https://help.github.com/categories/receiving-notifications-about-activity-on-github/) en *GitHub Help*.

  ```
  @githubteacher
  ```

  @githubteacher

  <hr>
</details>

<details>
  <summary>Enlaces cruzados</summary>

  ### Enlaces cruzados

  Para obtener una lista de propuestas (o _issues_) y solicitudes de extracción (o _pull requests_) en un repositorio, teclea `#`. Escribe el número o el título de la propuesta o solicitud de extracción para filtrar la lista, y presiona el Tabulador o Enter para completar el resultado resaltado.
  
  Además, las referencias a propuestas o solicitudes de extracción se convierten automáticamente en enlaces abreviados a la propuesta o solicitud de extracción en cuestión. Por ejemplo,
  
  | Tipo de referencia | Referencia en bruto | Enlace abreviado |
  | -------------- | ------------- | ---------- |
  |  URL de la propuesta o solicitud de extracción | `https://github.com/desktop/desktop/pull/3602` | [#3602](https://github.com/desktop/desktop/pull/3602) |
  | `#` seguido del número de la propuesta o solicitud de extracción | #3602 | [#3602](https://github.com/desktop/desktop/pull/3602) |
  | `GH-` seguido del número de la propuesta o solicitud de extracción | GH-3602 | [GH-3602](https://github.com/desktop/desktop/pull/3602) |
  | `Username/Repository#` seguido del número de la propuesta o solicitud de extracción | desktop/desktop#3602 | [desktop/desktop#3602](https://github.com/desktop/desktop/pull/3602) |

  Para más información, consulta “[Autolinked references and URLs](https://help.github.com/articles/autolinked-references-and-urls/)” en *GitHub Help*.

  <hr>
</details>

<details>
  <summary>Enlazando cambios confirmados (o _commits_) específicos</summary>

  ### Enlazando cambios confirmados (o _commits_) específicos

  Las referencias a la ID de una confirmación de cambios (generalmente denominada SHA o 'hash') se convierten automáticamente en enlaces abreviados a esa confirmación de cambios (o _commit_) en GitHub. Por ejemplo,
  
  | Tipo de referencia | Referencia en bruto | Enlace abreviado |
  | -------------- | ------------- | ---------- |
  | URL del commit | https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | SHA | 8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | Usuario@SHA | desktop@8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [desktop@8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | Usuario/Repositorio@SHA | User/Repository@SHA: desktop/desktop@8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [desktop/desktop@8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87)|


  <hr>
</details>

### Formateando con Markdown

<details>
  <summary>Citas</summary>

  ### Citas

  Puedes introducir citas textuales con `>`.

  ```
  En palabras del sheriff Brody:

  > Necesitará otro barco más grande
  ```

  En palabras del sheriff Brody:

  > Necesitará otro barco más grande

  <hr>
</details>

<details>
  <summary>Tablas</summary>

   ### Tablas

   Puedes crear tablas juntando listas de palabras y separándolas con guiones `-` (para la primera fila), y después separando cada columna con una raya `|`:

    ```
    Primer encabezado | Segundo encabezado
    ----------------- | ------------------
    Contenido de la celda 1 | Contenido de la celda 2
    Contenido de la primera columna | Contenido de la segunda columna
    ```

  Primer encabezado | Segundo encabezado
  ----------------- | ------------------
  Contenido de la celda 1 | Contenido de la celda 2
  Contenido de la primera columna | Contenido de la segunda columna

  Para más detalles acerca de formatear tablas, consulta "Organizing information with tables" en _GitHub Help_.

<hr>
</details>

<details>
  <summary>Bloques de código en línea</summary>

  ### Bloques de código en línea

  Algunas palabras y frases necesitan formatearse con tipografías monoespaciadas, especialmente al escribir acerca de código. Como has ido viendo a lo largo de este curso, algunas palabras pueden distinguirse en Markdown como `bloques de código en línea`.

  El código en línea es simplemente un carácter ``` a cada lado del texto, y puede usarse en párrafos, encabezados y otros elementos Markdown.

  ```
  `el código en línea es simplemente un acento invertido`
  ```

  `el código en línea es simplemente un acento invertido`

  <hr>
</details>

<details>
  <summary>Bloques de código separados</summary>

  ### Bloques de código separados

  Para separar fragmentos de código más largos, utiliza tres caracteres ``` en vez de uno, y coloca el texto en su propio párrafo.
  
  Lo que escribimos:
  
    ```
    Cualquier cosa escrita en este **párrafo** no será _formateado_ incluso aunque normalmente fuera a ser reconocido en este contexto. :taco:
    ```
    
  Lo que vemos:
  
  ```
  Cualquier cosa escrita en este **párrafo** no será _formateado_ incluso aunque normalmente fuera a ser reconocido en este contexto. :taco:
  ```
<hr>
</details>

<details>
  <summary>Resaltado de sintaxis</summary>

  ### Resaltado de sintaxis

  Además de los bloques de código, algunos de ellos deberían mostrarse de maneras diferentes según el lenguaje de programación que se use, como JavaScript o texto de línea de comandos.
  
  Lo que escribimos:

      ```sh
      github-learning-lab ~/Projects/recipe-repository
      $ git init
      Initialized empty Git repository in /Users/github-learning-lab/Projects/recipe-repository/.git/
      ```

  Lo que vemos:
  ```sh
  github-learning-lab ~/Projects/recipe-repository
  $ git init
  Initialized empty Git repository in /Users/github-learning-lab/Projects/recipe-repository/.git/
  ```
  <hr>
</details>

<details>
  <summary>Desplegable de resumen</summary>

  ### Desplegable de resumen

  La mayoría del texto en esta propuesta esta formateado en bloques de texto despegables. Así es como puedes hacerlos con Markdown:

  ```
  <details>
    <summary>Título</summary>

    El contenido aquí.

  </details>
  ```

  <hr>
</details>

¿Quieres seguir aprendiendo? Puedes [comprobar otros cursos]({{ host }}/courses).

<hr>
<h3 align="center">No responderé a esta propuesta, simplemente ciérrala cuando hayas acabado.</h3>
