## Paso 5: Add an image

Now, you're going to add an image. You can add an image of yourself or anything else you'd like to feature. You'll also learn how to create descriptive text, or "alt text", for images, and how to create links.

### Images
Let's add an image. Don't forget to include descriptive text in the square brackets. This text is read aloud for people using screen readers. It's also shown at times when your image doesn't display, such as when there's a poor connection. You can see the syntax for images below:

```
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

### :keyboard: Actividad: Adding an image

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
1. As you did before, edit the file in this pull request.
2. In the file, replace the content in `_includes/02-image.md` with the correct Markdown for your image of choice. Don't forget to include alt-text!
3. Commit your changes.
{% endif %}

<hr>
<h3 align="center">Watch below for my response!</h3>
