## Step 7: Merge your image and link

This looks great, @{{ user.username }}! You've created a link to show off your portfolio, and now you can share it with the world.

### :keyboard: Activity: Merge the Pull Request

{% if preferences.gitTool == 'cli' %}
1. Check out to the `master` branch:
    ```shell
    git checkout master
    ```
2. Merge your branch:
    ```shell
    git merge add-images-links
    ```
3. Push the merged history to GitHub:
    ```shell
    git push
    ```
4. Delete your the branch locally:
    ```shell
    git branch -d add-images-links
    ```
{% else %}
1. Click **Merge pull request** below.
{% endif %}

<hr>
<h3 align="center">Watch below for my response!</h3>
