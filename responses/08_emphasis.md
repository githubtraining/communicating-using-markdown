## Step 9: Use emphasis

Great job with those lists! Let's try something new. You can use **bold** and _italic_ text in Markdown. There are a couple of ways to create emphasis.

```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

### :keyboard: Activity: Add some _emphasis_

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
1. Edit the file `_includes/05-emphasis.md` in this pull request.
1. Use the **Preview** tab and your :sparkles: new Markdown knowledge, add emphasis (like bold or italics) to your skills.
1. Enter a short and descriptive commit message.
1. Commit your changes.
{% endif %}

<hr>
<h3 align="center">Watch below for my response!</h3>
