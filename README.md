# Personal site

A lightweight personal website built with Jekyll and ready for GitHub Pages.

## Customize

1. Update the site details in `_config.yml`.
2. Update the portfolio copy in `index.md`, `about.md`, `projects.md`, and `experience.md`.
3. Add posts to `_posts/` using filenames such as `2026-01-01-my-post.md`.
4. Update the links in `_data/navigation.yml`.

## Preview locally

```sh
bundle install
bundle exec jekyll serve --livereload
```

Then open <http://localhost:4000>.

## Publish

Push the site to the default branch of a repository named `<username>.github.io`. In the repository settings, set **Pages → Build and deployment → Source** to **Deploy from a branch**, then select the default branch and `/ (root)`.
