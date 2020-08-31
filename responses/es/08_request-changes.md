Uh oh, we're not finding a list.

Remember the format for a list looks like this:

`- item`

It is important to put a space between the `-` or `*` and the list item text.

### :keyboard: Actividad: Add a list

{% if preferences.gitTool == 'cli' %}
1. In your shell, checkout to the branch in this pull request:
      ```shell
      git checkout add-lists-emphasis
      ```
1. In your text editor of choice, open the file called `04-lists.md`, in the `_includes` directory. Create a markdown list in the file. It can be ordered or unordered. Use either `-` or `*` to indicate the bullets.
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
1. Click the "Files changed" tab.
1. Scroll to find the `_includes/04-lists.md`.
1. Click the :pencil: pencil icon.
1. Add a list using either `-` or `*` to indicate the bullets.
1. Scroll to the bottom and commit your changes to your branch.
{% endif %}

If you would like assistance troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.

<hr>
<h3 align="center">Watch below for my response!</h3>
