:thinking: I don't see any text with emphasis yet. To complete this exercise, you need to add some emphasized text to the `_includes/05-emphasis.md` file, in the form of a *bold* or _italicized_ words.

### :keyboard: Activity: Add emphasis

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
1. Click the "Files changed" tab.
1. Scroll to find the `_includes/05-emphasis.md`.
1. Click the :pencil: pencil icon.
1. Add emphasis using `**` for **bold** or `_` for _italics_ (emphasis should not have a space between the markdown and the word to be modified).
1. Scroll to the bottom and commit your changes to your branch.
{% endif %}

If you would like assistance troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.

<hr>
<h3 align="center">Watch below for my response!</h3>
