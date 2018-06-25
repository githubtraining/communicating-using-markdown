# Communicating on GitHub

Can't interact with the GitHub Learning Lab app? No problem.
This course overview is here to help as a short walkthrough with a list of steps necessary to complete the "Communicating with Markdown" course and information provided by GitHub Learning Lab during the course.

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 orderedList:0 -->

- [Pre-work: Create Repository](#pre-work-create-repository)
- [Part 1: Get Started with Markdown](#part-1-get-started-with-markdown)
	- [What is markdown?](#what-is-markdown)
	- [Task Lists](#task-lists)
	- [:memo: Activity: Practice Markdown](#memo-activity-practice-markdown)
- [Part 2: Turn on GitHub Pages](#part-2-turn-on-github-pages)
	- [:memo: Activity: Enable GitHub Pages](#memo-activity-enable-github-pages)
- [Part 3: Outline your portfolio with headers](#part-3-outline-your-portfolio-with-headers)
	- [Headers](#headers)
	- [:memo: Activity: Edit your file with Headers](#memo-activity-edit-your-file-with-headers)
- [Part 4: Add an image](#part-4-add-an-image)
	- [Images](#images)
	- [:memo: Activity: Adding an Image](#memo-activity-adding-an-image)
- [Part 5: Emojis and Lists](#part-5-emojis-and-lists)
	- [:memo: Activity: Add a few details](#memo-activity-add-a-few-details)
- [Part 6: Fix broken markdown](#part-6-fix-broken-markdown)
	- [Emphasis](#emphasis)
	- [:memo: Activity: Fix the markdown](#memo-activity-fix-the-markdown)
- [Congratulations!](#congratulations)
	- [More Links in Markdown](#more-links-in-markdown)
	- [Formatting Markdown](#formatting-markdown)

<!-- /TOC -->

## Pre-work: Create Repository
- [ ] Use [GitHub Import tool]() to import [this template repository]() to your user's account
- [ ] Open an issue in the repository to practice Markdown

## Part 1: Get Started with Markdown

This repository is all about **communicating with Markdown**. The first thing to know about communicating with Markdown is that Markdown is an easy and widely used way to format your text.

This repository, and all of the activities you complete in it, will be working towards a static webpage with your customized resume information.

#### What is markdown?
Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.

Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`. You can use markdown with the toolbar in issues and pull requests, or you can learn the simple syntax and type it yourself.

You can use Markdown most places around GitHub:

- [Gists](https://gist.github.com/)
- Comments in Issues and Pull Requests (like this one!)
- Files with the `.md` or `.markdown` extension

For more information, see “[Writing on GitHub](https://help.github.com/categories/writing-on-github/)” in the GitHub Help.

#### Task Lists

A task list creates checkboxes that can be checked off by collaborators in a given repository. They're very handy for tracking issues, pull requests, and any to-do item.

If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

Watch out, because the syntax for task lists is very specific. Be sure to include the spaces where required, or else they won't work.


```
- [x] Other markdown is supported, including @mentions, #refs, [links](), **formatting**, and <del>tags</del>
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
  - Like this
- [x] this is a complete item
- [ ] this is an incomplete item

> _In the code block above, you can see how the text is typed originally. Then, you see how it will be formatted with Markdown. Keep an eye out for this pattern throughout the course. :eyes:_

### :memo: Activity: Practice Markdown
1. Leave a comment to this issue. Use markdown to create a list of todo items:
	- Turn on GitHub Pages
	- Outline my portfolio
	- Introduce myself to the world

Throw in an emoji for fun :rainbow: Good luck!

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._

## Part 2: Turn on GitHub Pages

Nicely done! Your markdown to-do list looks great. :sparkles:

Since this project is going to be a static web page, the first thing you'll need to do is turn on GitHub Pages. Here's how:

### :memo: Activity: Enable GitHub Pages
1. Under your repository name in this repository, click **Settings**.
      ![image of settings tab](https://help.github.com/assets/images/help/repository/repo-actions-settings.png)
1. Use the Select source drop-down menu to select `master` as your GitHub Pages publishing source.
      ![image of selecting a source](https://help.github.com/assets/images/help/pages/select-master-branch-docs-folder-as-source.png)
1. Click **Save**.
      ![image of clicking save](https://help.github.com/assets/images/help/pages/click-save-next-to-master-branch-docs-folder-source-selection.png)

> _You can find the full instructions and more information on GitHub Pages [here](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/)._

## Part 3: Outline your portfolio with headers

As you saw on your website, the current resume is pretty sparse. The first steps you'll take to improve it are:
- Edit the file in this pull request
- Use Markdown headers to bolster the resume outline

#### Headers

An example of a header is, well, the header at the beginning of this issue! Just like in any text editing software, a header is a larger bit of text at the beginning of a section.

```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```

The fewer the `#`, the larger the header.

In issues, pull requests, and comments, you can use the text formatting toolbar.

![](https://help.github.com/assets/images/help/writing/markdown-toolbar.gif)

But, the toolbar isn't available everywhere. As you edit your file, you'll need to type the `#` symbols by hand.

### :memo: Activity: Edit your file with Headers
1. Create a branch in this repository.
1. In the `README.md` file, add a `#` before the content on line 1 so it formats as a "header 1". Use the same concept to turn the other lines into headers, using 1 through 6 hash symbols.
      ![headers](https://help.github.com/assets/images/help/writing/headings-rendered.png)
1. Above the new content, click **Preview changes**.
      ![preview changes](https://help.github.com/assets/images/help/repository/edit-readme-preview-changes.png)
1. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file.
      ![make a commit on GitHub](https://help.github.com/assets/images/help/repository/write-commit-message-quick-pull.png)
1. Commit your changes.
1. Open a pull request.

> _Not sure how to create branches, make commits, or open pull requests? Try the [Introduction to GitHub]() course first._

## Part 4: Add an image

Next, you're going to add an image. You can add an image of yourself, or of something else you'd like to feature. You'll also learn how to create alt-text for images, and how to create links.

#### Images
If you want to embed images, this is how you do it. Don't forget to include descriptive text in the square brackets for those using screen readers, or in case your image doesn't display for some reason.

```
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

### :memo: Activity: Adding an Image
1. Edit the file in the pull request you created in Part 3.
2. Look for the text "add an image here" on line 3. Replace that text with the markdown to feature your image of choice. Don't forget to include alt-text!
3. Commit your changes.

## Part 5: Emojis and Lists

In this PR, you'll learn lists and emojis. You'll also list a few details in your resume!

:point_down: _These are expandable dialogues! Click to open and see more information._

<details>
  <summary>Emoji</summary>

  #### Emoji

  Emoji are fun :sparkles:, and they can be silly :stuck_out_tongue_winking_eye:, but they can also be an important communication tool when working with remote teams ✅. Tone doesn't come across as clearly when reading text as it comes speaking face to face, and emojis can be helpful in conveying context and emotions. :heart:

  Here are some examples of popular emojis in markdown.

  | What you see | What you type |
  | ---------- | ------------ |
  | :heart:    | `:heart:`    |
  | :+1:       | `:+1:`       |
  | :smile:    | `:smile:`    |
  | :sparkles: | `:sparkles:` |
  | :tada:     | `:tada:`     |

  If you aren't sure what emojis are possible, you can [look them up on a cheatsheet](https://gist.github.com/rxaviers/7360908). In many places on GitHub, you can type `:` and then begin to type the name of an emoji. A fuzzy search will bring up the 5 best guesses and let you select one.

  ![image of fuzzy search emojis on GitHub](https://user-images.githubusercontent.com/9906718/34602228-47cab148-f1ff-11e7-91f1-56d0fed702f0.png)
  <hr>
</details>


<details>
  <summary>Ordered Lists</summary>

  #### Ordered Lists

  Ordered lists have numbers and can have indented children that are also ordered.

  When you're creating ordered lists, you can type out the exact number you want to show in order, (1, 2, 3, etc.) but you can also type every number as "1.". Markdown will take care of the rest of the numbering for you, and your list will be easier to maintain.

  ```
  1. Item 1
  1. Item 2
  1. Item 3
     1. Item 3a
     1. Item 3b
  ```

  1. Item 1
  1. Item 2
  1. Item 3
     1. Item 3a
     1. Item 3b

 <hr>
</details>

<details>
 <summary>Unordered Lists</summary>

  #### Unordered Lists

  To create an unordered list, you can use the `-` character or the `*` character. To do an indented child list item, you need to type a tab or at least two spaces.

  ```
  * Item 1
  * Item 2
    * Item 2a
    * Item 2b
  ```

  * Item 1
  * Item 2
    * Item 2a
    * Item 2b

  <hr>
</details>

I've started a list for you in the "accomplishments" section. Your next steps are to fill out that list, and add another one somewhere else.
> _Not sure what to type? That's OK! Create a fictional resume based on your favorite movie or book character!_

### :memo: Activity: Add a few details
1. Like before, edit the file in this pull request.
1. Look for the incomplete list. Fill in the items so the list has actual content.
1. Create another list somewhere in the resume. It could be ordered or unordered.
1. Commit your changes.

## Part 6: Fix broken markdown
In the repository you imported, there's an existing branch called `broken-markdown`. Soon, you'll get to fix it, but first you'll need to know about emphasis in markdown.

#### Emphasis

You can also use **bold** and _italic_ text in markdown. In markdown, sometimes there are multiple ways to accomplish the same goal.

```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

### :memo: Activity: Fix the markdown

1. Create a pull request with `base: master` and `compare: fix-markdown`.
1. Edit the file in this pull request.
1. By using the **Preview** tab and your :sparkles: new Markdown knowledge, see what markdown is broken.
1. Fix the markdown.
  - You'll know the markdown is fixed when the formatting works, and there are no additional markdown characters around that don't do anything. You might need to delete or add markdown to make it work correctly.

## Congratulations!
You've done it. You're done with the course, but here's some quick information about some of the other cool features we didn't cover.

### More Links in Markdown

<details>
  <summary>Linking SHAs</summary>

  #### Linking SHAs

  References to a commit's SHA hash are automatically converted into shortened links to the commit on GitHub. For example,

  | Reference type | Raw reference | Short link |
  | -------------- | ------------- | ---------- |
  | Commit URL | https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e | [a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |
  | SHA | a5c3785ed8d6a35868bc169f07e40e889087fd2e | [a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |
  | User@SHA | jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e | [jlord@a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |
  | Username/Repository@SHA | User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e | [jlord/sheetsee.js@a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e)|  


  <hr>
</details>

<details>
  <summary>Cross Links</summary>

  #### Cross Links

  You can bring up a list of suggested issues and pull requests within the repository by typing #. Type the issue or pull request number or title to filter the list, and then press either tab or enter to complete the highlighted result.

  Additionally, references to issues and pull requests are automatically converted to shortened links to the issue or pull request. For example,

  | Reference type | Raw reference | Short link |
  | -------------- | ------------- | ---------- |
  | Issue or pull request URL | https://github.com/jlord/sheetsee.js/issues/26 | [#26](https://github.com/jlord/sheetsee.js/issues/26) |
  | `#` and issue or pull request number | #26 | [#26](https://github.com/jlord/sheetsee.js/issues/26) |
  | `GH-` and issue or pull request number | GH-26 | [GH-26](https://github.com/jlord/sheetsee.js/issues/26) |
  | `Username/Repository#` and issue or pull request number | jlord/sheetsee.js#26 | [jlord/sheetsee.js#26](https://github.com/jlord/sheetsee.js/issues/26) |

  <hr>
</details>

<details>
<summary>Username and Team @mentions</summary>

	#### Username and Team @mentions
	Typing an `@` symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also `@mention` teams within an organization.

	```
	@githubteacher
	```

	@githubteacher

<hr>
</details>

### Formatting Markdown

<details>
  <summary>Quotes</summary>

  #### Quotes

  You can quote text with a `>`.

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

   #### Tables

   You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

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

<hr>
</details>

<details>
  <summary>Inline Code Blocks</summary>

  #### Inline Code Blocks

  Sometimes, it makes text easier to read if you specify a certain term as `code`. The word "code" in the previous sentence was distinguished in markdown with `inline code blocks`.

  Inline code is just one ``` character on either side of the text, and can be used within paragraphs, headers, or other markdown.

  ```
  `inline code is just one backtick`
  ```

  `inline code is just one backtick`

  <hr>
</details>

<details>
  <summary>Separate Code Blocks</summary>

  #### Separate Code Blocks

  If you need to separate out a larger block of code, use three ``` characters instead of one, and set the text aside in its own paragraph. This is how the course shows you how markdown looks without actually formatting it.

  ```
  Anything put in this **paragraph** will not be _formatted_ even if it would normally be recognized in this setting. :taco:
  ```

  Anything put in this **paragraph** will not be _formatted_ even if it would normally be recognized in this setting. :taco:
  <hr>
</details>

<details>
  <summary>Syntax Highlighting</summary>

  #### Syntax Highlighting

  In addition to code blocks, you can specify how the code should be formatted by language. For example, take a look at this JavaScript code in a regular code block:

  What we type:
      ```
      function fancyAlert(arg) {
        if(arg) {
          $.facebox({div:'#foo'})
        }
      }
      ```

  What we see:
  ```
  function fancyAlert(arg) {
    if(arg) {
      $.facebox({div:'#foo'})
    }
  }
  ```

  But, when we add the language after the first three ``` characters, the formatting is specific to the programming language.

  What we type:
      ```javascript
      function fancyAlert(arg) {
        if(arg) {
          $.facebox({div:'#foo'})
        }
      }
      ```

  What we see:
  ```javascript
  function fancyAlert(arg) {
    if(arg) {
      $.facebox({div:'#foo'})
    }
  }
  ```
  <hr>
</details>
