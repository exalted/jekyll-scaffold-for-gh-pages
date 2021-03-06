# About

This repository is a bare scaffold for [Jekyll](http://jekyllrb.com), ready to be published on [GitHub Pages](https://pages.github.com) and some workflow goodies for development and publishing.


# Info

Known to be working and scaffolded with `bundle exec jekyll --version # jekyll 3.0.2`.


# Getting Started

```
git clone https://github.com/exalted/jekyll-scaffold-for-gh-pages.git --origin scaffold my-awesome-website
cd my-awesome-website/
git remote add origin <url of your new GitHub repository>
script/bootstrap
```


# Preview Locally

```
bin/serve
```


# Publish on GitHub Pages

```
bin/publish
```

:warning: Don't forget to at least configure properly `baseurl` in `_config.yml` before publishing using GitHub Pages ([read more](http://jekyllrb.com/docs/github-pages/#project-page-url-structure).)

Learn more about [GitHub Pages Features](https://help.github.com/categories/github-pages-features/).


# For Developers

## Update gems

```
bundle update # make sure to update this readme with latest jekyll version number.
```

## Update scaffold

In order to update for a different scaffolded (ideally vanilla and up-to-date rather than customized or superseded), with a clean working directory, do:

```
bundle exec jekyll new --force .
```

This *may* override bunch of files and you should be looking for what's modified and decide how to go about each change.
