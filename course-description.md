# Communicating with Markdown

This document contains the course flow for the "Communicating with Markdown" course.

In this course, you'll learn:
- Markdown, including
  - headers
  - lists
  - images
  - links
  - more!
- Where to use Markdown
  - issues
  - pull requests
  - `.md` files

### User Registration
- Before registration, a description of the class and the recommended prerequisites will be available.
- Bot sets up template repo (bare bones `README`)
- Bot creates first issue with instructions to create a tasklist as a comment. (title: Getting Started with Markdown, content: 01-welcome.md)


----
| Student action | App response |
| -------------- | ------------ |
| Writes a task list | Comments in issue #1 to enable pages (01a-turn-on-ghp.md) |
| Enable GitHub Pages from `master` | Comments in issue #1 congrats (01b-close-issue.md), Opens PR #2 (title: Outline your portfolio, body-contents: 02-headers.md, pr-contents: 02-resume.md) |
| Edit file in PR #2 by adding header formatting | Validate via status check and/or PR review, comments (03-pr-succeeds.md) or (03-request-changes.md) |
| Merge pull request #2 | Comments (03-next.md) in PR #2, opens PR #3 (title: Introduce yourself to the world, body-contents: 04-add-image.md, pr-contents: "Add image here" on line 2 or 3 of README.md) |
| Add's image in PR #3 | Validate via status check and/or PR review, comments (04-image-works-url.md) or (04-request-changes.md) |
| Comment with URL to their GH Pages site | Comments (04-success.md) |
| Merges PR #4 | Comments (04-next.md), opens PR #5 (title: Adding a few details, body-contents: 05-pr-body.md, pr-contents: Starting a list under one of the headers) |
| Comments in PR #4 with list of emoji (at least 2, any type of list) | Comments (05-edit-pr.md) |
| Edits PR with lists | Validate via status check and/or PR review, comments (05-success.md) or (05-request-changes.md) |
| Merge PR #5 | Comments (05-next.md), opens PR #6 (title: Fix broken markdown, body-contents: 06-fix-markdown.md, pr-contents: adding markdown in new sections that is broken) |
| Fix the markdown | Validate via status check and/or PR review, comments (06-success.md) or (06-request-changes.md) |
| Merge PR #6 | Comments (06-next.md), Opens issue (title: More to Learn, body: 07-more-to-learn.md) |
