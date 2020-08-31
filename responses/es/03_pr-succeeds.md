## Step 4: Merge your headers

I see you've added at least one header, @{{ user.username }}. You can continue working if you'd like, otherwise let's merge <sup>[:book:](https://help.github.com/articles/github-glossary/#merge)</sup> this pull request and move on with the course.

### :keyboard: Activity: Merge the Pull Request

{% if preferences.gitTool == 'cli' %}
1. Check out to the `master` branch:
    ```shell
    git checkout master
    ```
2. Merge your branch:
    ```shell
    git merge add-headers
    ```
3. Push the merged history to GitHub:
    ```shell
    git push
    ```
4. Delete your the branch locally:
    ```shell
    git branch -d add-headers
    ```
{% else %}
1. Click **Merge pull request** below.
{% endif %}

<hr>
<h3 align="center">Watch below for my response!</h3>
