## Step 3: Add headers

As you saw on your website, your portfolio doesn't have much content yet. We'll learn how to edit the file in this pull request to incorporate some Markdown headers.

You can see an example of a header at the top of this page! Just like in HTML, a header is a larger bit of text at the beginning of a section. There are six sizes.

#### Example

```
# This is an <h1> header, which is the largest
## This is an <h2> header
###### This is an <h6> header, which is the smallest
```

#### How it looks

# This is an `<h1>` header, which is the largest
## This is an `<h2>` header
###### This is an `<h6>` header, which is the smallest

In issues, pull requests, and comments, you can use the text formatting toolbar.

The toolbar isn't available everywhere. When you edit a file, you must type the `#` symbols manually.

### :keyboard: Activity: Edit your file with headers

{% if preferences.gitTool == 'cli' %}
1. Open your preferred command line interface, which we'll call your shell from now on.
1. Clone this repository:
      ```shell
      git clone {{ thePayload.repository.clone_url }}
      ```
1. Navigate to the repository in your shell:
      ```shell
      cd {{ thePayload.repository.name }}
      ```
1. Checkout to the branch in this pull request:
      ```shell
      git checkout add-headers
      ```
1. In your text editor of choice, open the file called `01-name.md`, in the `_includes` directory. On the first line, replace the text with your name, and add a `#` before the content to make it an H1 Header.
1. Save your file. Every time you make changes, it's a good idea to type `git status`. You should type this after you stage files, and after you commit. It's always a good idea!
1. Stage your file:
      ```shell
      git add _includes/01-name.md
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
1. In this pull request, click the **Files changed** tab.
1. In the upper right corner of the file view, click the **small pencil** ✏️ icon for the file titled `_includes/01-name.md`.
1. On the **Edit file** tab, add a `#` before the content to make it an H1 Header. You can add more headers, using one to six `#` characters.
1. Above your new content, click **Preview changes**.
1. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file.
1. Click **Commit changes**.
{% endif %}

<hr>
<h3 align="center">Watch below for my response.</h3>
