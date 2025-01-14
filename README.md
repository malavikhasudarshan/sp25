# Data 100 Website Spring 2025

[![Pages Deployment](https://github.com/berkeley-cdss/berkeley-class-site/actions/workflows/jekyll.yml/badge.svg)](https://github.com/berkeley-cdss/berkeley-class-site/actions/workflows/jekyll.yml) •
[![a11y specs](https://github.com/berkeley-eecs/berkeley-class-site/actions/workflows/rspec.yml/badge.svg)](https://github.com/berkeley-eecs/berkeley-class-site/actions/workflows/rspec.yml)


## Installation

Prerequisites:

- You have everything that [Jekyll requires](https://jekyllrb.com/docs/installation/)
- You have installed [Bundler](https://bundler.io/): Run `gem install jekyll bundler`

After cloning this repository and navigating into the directory, run the following command to install dependencies
```
cd YOUR_REPO
bundle install
```

## Usage

To run the site locally, run:

```
bundle exec jekyll serve
```

## Deployment

This site is deployed via a [GitHub Action Workflow](.github/workflows/jekyll.yml). For more information see [GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

## License

[MIT](LICENSE)
