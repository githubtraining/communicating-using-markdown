## Paso 6: Add a profile link

Your image looks great! Next, you'll want to add links to your awesome portfolio projects. Links help create context when you’re communicating in issues and pull requests.

You might link to a [website](https://github.com/), a [repository](https://github.com/github/training-kit), or even a [line of code](https://github.com/github/training-kit/blob/master/resources/learning-path/index.html#L32). To create a link, put the text you want to display in square brackets, and the URL in the following parentheses.

```
[GitHub](http://github.com)
```

## :keyboard: Actividad: Add a link

{% if preferences.gitTool == 'cli' %}
1. In your shell, verify that you are currently checked out to the branch `add-images-links`:
      ```shell
      git status
      ```
1. If you are _not_, then checkout to that branch:
      ```shell
      git checkout add-images-links
      ```
1. In your text editor of choice, open the file called `03-links.md`, in the `_includes` directory. Replace the filler text with a link to your GitHub profile (or anywhere else).
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/03-links.md
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
1. Edit the file `_includes/03-links.md`.
1. Replace the filler text with a link to your GitHub profile (or anywhere else).
{% endif %}

<hr>
<h3 align="center">Watch below for my response!</h3>
