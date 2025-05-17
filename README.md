# notes.linderttobias.com

Welcome to the repository for [notes.linderttobias.com](https://notes.linderttobias.com), a personal blog powered by Jekyll and GitHub Pages. This blog serves as a place where I share my thoughts, ideas, and notes on various topics.

## Features

- **Jekyll-powered**: This site is built using [Jekyll](https://jekyllrb.com/), a static site generator that makes it easy to create and manage blog content.
- **GitHub Pages**: Hosted on GitHub Pages for easy deployment and version control.

## Usage

### Write new blog posts

Adding new blog posts is simple:


1. Navigate to the `_posts` directory.  
2. Create a new file called `YYYY-MM-DD-NAME-OF-POST.md`, replacing YYYY-MM-DD with the date of your post and NAME-OF-POST with the name of your post.
3. Add the following YAML frontmatter to the top of the file, including the post's title enclosed in quotation marks, the date and time for the post in YYYY-MM-DD hh:mm:ss -0000 format, and as many categories as you want for your post.
    ```
    layout: post
    title: "POST-TITLE"
    date: YYYY-MM-DD hh:mm:ss -0000
    categories: CATEGORY-1 CATEGORY-2
    ---
    ```
4. Below the frontmatter, add content for your post.

### Publish new blog posts



1. Navigate to the `docs` directory.
2. `bundle exec jekyll serve`
3. Visit `localhost:4000`
4. `If you==happy (add,commit,push) else (rewrit)`
