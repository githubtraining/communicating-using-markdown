## Paso 8: Add a list

In this pull request, you'll learn about lists and emoji. You'll also list a few details in your resume.

:point_down: _These are expandable dialogues! Click to open and see more information._

<details>
  <summary>Emoji</summary>

  ### Emoji

  Emoji are fun :sparkles:, and they can be silly :stuck_out_tongue_winking_eye:, but they can also be an important communication tool when working with remote teams ✅. Tone doesn't come across as clearly when reading text as it comes speaking face to face, and emojis can be helpful in conveying context and emotions. :heart:

  Emoji are best used as additive extras, not replacements for text. With images, descriptive text makes it clearer for screen readers, but screen readers aren't guaranteed to convey the intent of an emoji. Make sure your meaning is clear in text, so emoji will help instead of causing more confusion.

  Here are some examples of popular emojis in markdown.

  | What you see | What you type |
  | ---------- | ------------ |
  | :heart:    | `:heart:`    |
  | :+1:       | `:+1:`       |
  | :smile:    | `:smile:`    |
  | :sparkles: | `:sparkles:` |
  | :tada:     | `:tada:`     |

  For more information about available emoji, [see this handy cheat sheet](https://gist.github.com/rxaviers/7360908). In most text fields on GitHub, you can type `:` and then begin to type the name of an emoji. A fuzzy search will bring up the 5 best guesses and let you select one.

  ![image of fuzzy search emojis on GitHub](https://user-images.githubusercontent.com/9906718/34602228-47cab148-f1ff-11e7-91f1-56d0fed702f0.png)
  <hr>
</details>


<details>
  <summary>Ordered Lists</summary>

  ### Ordered Lists

  Ordered lists have numbers. You can nest ordered lists within a list item by indenting them. You can read more about [formatting and syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/) in the _GitHub Help_.

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
 <summary>Unordered Lists</summary>

  ### Unordered Lists

  To create an unordered list, use either the `-` or `*` character. As with ordered lists, you can nest a list by indenting two spaces.

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

### Adding a list

Help people get to know you by adding a list containing a few of your favorite things. Don't know what to add? Why not add a list of your favorite books or places to eat.

### :keyboard: Actividad: Create a list

{% if preferences.gitTool == 'cli' %}
1. In your shell, checkout to the branch in this pull request:
      ```shell
      git checkout add-lists-emphasis
      ```
1. In your text editor of choice, open the file called `04-lists.md`, in the `_includes` directory. Create a markdown list in the file. It can be ordered or unordered.
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/04-lists.md
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
1. Edit the `_includes/04-lists.md` in this pull request.
1. Create a markdown list in the file. It can be ordered or unordered.
1. Commit your changes.
{% endif %}

<hr>
<h3 align="center">Watch below for my response!</h3>
