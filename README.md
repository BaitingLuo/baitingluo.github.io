# baitingluo.github.io

Source for [baitingluo.github.io](https://baitingluo.github.io/), Baiting Luo's personal site. It is a Jekyll site based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template and is published by GitHub Pages from the `master` branch.

- `_pages/about.md`: home page (About, Services, Research)
- `_publications/*.md`: one file per publication; `category` must be a key under `publication_category` in `_config.yml`, and optional `paperurl`, `codeurl`, and `award` fields render as links and a tag
- `files/Baiting_CV.pdf`: the CV behind the CV menu item
- `_config.yml`: site, sidebar, and publication category settings

Local preview: `bundle install && bundle exec jekyll serve`, then open http://localhost:4000.
