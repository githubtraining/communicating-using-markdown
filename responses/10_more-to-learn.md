## Nice work

Congratulations @{{ user.username }}, you've completed this course!

![congratulations](https://octodex.github.com/images/welcometocat.png)

## What went well

During this course you successfully:

- Added a checklist to an issue comment
- Enabled GitHub Pages on your repository
- Committed changes to your webpage by:
    - Adding headers to the `01-name.md` file
    - Including an image in the `02-image.md` file
    - Creating links to other websites in the `03-links.md` file
    - Adding your accomplishments to the `04-lists.md` file
    - Using emphasis like **bold** and _italics_ in the `05-emphasis.md` file

## What's next?

Now that you have mastered the basics of Markdown @{{ user.username }}, here's some quick information about some of the other cool features we didn't cover.

### More Links in Markdown

<details>
<summary>Username and Team @mentions</summary>

  ### Username and Team @mentions

  Typing an `@` symbol, followed by a GitHub username, will send a notification to that person about the comment. This is called an “@mention”, because you’re mentioning the individual. You can also `@mention` teams within an organization. For more information, see “[Receiving notifications about activity on GitHub](https://help.github.com/categories/receiving-notifications-about-activity-on-github/) in the *GitHub Help*.

  ```
  @githubteacher
  ```

  @githubteacher

  <hr>
</details>

<details>
  <summary>Cross Links</summary>

  ### Cross Links

  To bring up a list of suggested issues and pull requests within a repository, type `#`. Type the issue or pull request number or title to filter the list, and then press either Tab or Enter to complete the highlighted result.

  Additionally, references to issues and pull requests are automatically converted to shortened links to the issue or pull request. For example,

  | Reference type | Raw reference | Short link |
  | -------------- | ------------- | ---------- |
  | Issue or pull request URL | `https://github.com/desktop/desktop/pull/3602` | [#3602](https://github.com/desktop/desktop/pull/3602) |
  | `#` and issue or pull request number | #3602 | [#3602](https://github.com/desktop/desktop/pull/3602) |
  | `GH-` and issue or pull request number | GH-3602 | [GH-3602](https://github.com/desktop/desktop/pull/3602) |
  | `Username/Repository#` and issue or pull request number | desktop/desktop#3602 | [desktop/desktop#3602](https://github.com/desktop/desktop/pull/3602) |

  For more information, see “[Autolinked references and URLs](https://help.github.com/articles/autolinked-references-and-urls/)” in the *GitHub Help*.

  <hr>
</details>

<details>
  <summary>Linking Specific Commits</summary>

  ### Linking Specific Commits

  References to a commit's ID (commonly called a SHA or hash) are automatically converted into shortened links to the commit on GitHub. For example,

  | Reference type | Raw reference | Short link |
  | -------------- | ------------- | ---------- |
  | Commit URL | https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | SHA | 8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | User@SHA | desktop@8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [desktop@8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87) |
  | Username/Repository@SHA | User/Repository@SHA: desktop/desktop@8304e9c271a5e5ab4fda797304cd7bcca7158c87 | [desktop/desktop@8304e9c](https://github.com/desktop/desktop/commit/8304e9c271a5e5ab4fda797304cd7bcca7158c87)|


  <hr>
</details>

### Formatting Markdown

<details>
  <summary>Quotes</summary>

  ### Quotes

  You can create quote text with a `>`.

  ```
  In the words of Abraham Lincoln:

  > Pardon my French
  ```

  In the words of Abraham Lincoln:

  > Pardon my French

  <hr>
</details>

<details>
  <summary>Tables</summary>

   ### Tables

   You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:

    ```
    First Header | Second Header
    ------------ | -------------
    Content from cell 1 | Content from cell 2
    Content in the first column | Content in the second column
    ```

  First Header | Second Header
  ------------ | -------------
  Content from cell 1 | Content from cell 2
  Content in the first column | Content in the second column

  For more detail on formatting with tables, see "Organizing information with tables" in the _GitHub Help_.

<hr>
</details>

<details>
  <summary>Inline Code Blocks</summary>

  ### Inline Code Blocks

  Certain words and phrases need to be formatted in monospace fonts, especially when writing about code. As you've seen throughout this lab, words can be distinguished in markdown with `inline code blocks`.

  Inline code is just one ``` character on either side of the text, and can be used within paragraphs, headers, or other Markdown.

  ```
  `inline code is just one backtick`
  ```

  `inline code is just one backtick`

  <hr>
</details>

<details>
  <summary>Separate Code Blocks</summary>

  ### Separate Code Blocks

  To separate out a larger block of code, use three ``` characters instead of one, and set the text aside in its own paragraph.

  What we type:
  
    ```
    Anything written in this **paragraph** will not be _formatted_ even if it would normally be recognized in this setting. :taco:
    ```
    
  What we see:
  
  ```
  Anything written in this **paragraph** will not be _formatted_ even if it would normally be recognized in this setting. :taco:
   ```
<hr>
</details>

<details>
  <summary>Syntax Highlighting</summary>

  ### Syntax Highlighting

  In addition to code blocks, some code blocks should be rendered differently depending on the language, such as Javascript or command-line text.

  What we type:

      ```sh
      github-learning-lab ~/Projects/recipe-repository
      $ git init
      Initialized empty Git repository in /Users/github-learning-lab/Projects/recipe-repository/.git/
      ```

  What we see:
  ```sh
  github-learning-lab ~/Projects/recipe-repository
  $ git init
  Initialized empty Git repository in /Users/github-learning-lab/Projects/recipe-repository/.git/
  ```
  <hr>
</details>

<details>
  <summary>Summary dropdown</summary>

  ### Summary dropdown

  Most of the text in this issue is formatted in collapsible summary blocks. Here's how to make them with Markdown:

  ```
  <details>
    <summary>Title</summary>

    Content here

  </details>
  ```

  <hr>
</details>

Want to keep learning? Feel free to [check out our other courses]({{ host }}/courses).

<hr>
<h3 align="center">I won't respond to this issue, just close it when you are done!</h3>
