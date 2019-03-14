Something doesn't look quite right with this image. Make sure:

- The placeholder text is deleted
- Your image formatting is correct (`![alt-text](image-url)`)
- The image has alt text

### :keyboard: Activity: Add an image

{% if preferences.gitTool == 'cli' %}
1. In your shell, checkout to the branch in this pull request:
      ```shell
      git checkout add-images-links
      ```
1. In your text editor of choice, open the file called `02-image.md`, in the `_includes` directory. In the file, replace the content with the correct Markdown for your image of choice. Don't forget to include alt-text!
1. Save your file.
1. Stage your new file:
      ```shell
      git add _includes/02-image.md
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
1. Scroll to find the `_includes/02-image.md`.
1. Click the :pencil: pencil icon.
1. Add an image using the syntax `![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)`.
1. Scroll to the bottom and commit your changes to your branch.
{% endif %}

If you would like assistance troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.

<hr>
<h3 align="center">Watch below for my response!</h3>
