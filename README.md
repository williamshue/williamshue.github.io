# williamshue.net

Personal site and blog, built with Jekyll and published to GitHub Pages.

## Write a post

1. Add a file to `_posts/` named `YYYY-MM-DD-short-title.md`.
2. Start it with:

   ```
   ---
   layout: post
   title: Your title
   math: true        # only if the post has equations
   ---
   ```

3. Write in Markdown.
   - Code: fence it with three backticks and the language, e.g. ```` ```python ````.
   - Math: wrap LaTeX in `$$ ... $$`. Inline in a sentence, or on its own lines for a centered equation.
4. Commit and push. The site rebuilds in about a minute and the post appears on the homepage.

## Preview on your own machine

```
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Photo

Save a square photo as `assets/me.jpg`, then in `index.html` replace the empty `<div class="photo">` with:

```html
<img class="photo" src="/assets/me.jpg" alt="William Shue">
```
