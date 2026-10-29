# Portfolio

A personal portfolio website built with Markdown and Jekyll for GitHub Pages.
It highlights an introduction, skills and tools, selected projects, and contact
information.

## Features

- Responsive layout with a dark theme and teal accents
- About, skills, projects, and contact sections
- Minima theme with custom Sass styling
- Designed to publish as a GitHub Pages site

## Customize

Update `index.md` with your name, introduction, skills, project details, and
contact email. Replace the sample GitHub links with links to your own work.
Change the site title and description in `_config.yml`.

## Local preview

GitHub Pages builds the site with Jekyll. To preview locally, install Ruby and
Jekyll, then run:

```sh
gem install jekyll minima
```

```sh
jekyll serve
```

Then open http://127.0.0.1:4000 in your browser. 
Leave the command running while you view the site.
press Ctrl+C to stop it. You’ll need Ruby installed first.

## Publish

Push the repository to GitHub and enable GitHub Pages for the repository in
**Settings → Pages**. Select the branch and folder containing the site files.