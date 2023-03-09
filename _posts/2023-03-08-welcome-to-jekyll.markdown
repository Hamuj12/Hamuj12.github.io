---
layout: post
title:  "Building my personal website with Jekyll"
date:   2023-03-08 22:17:55 -0600
categories: jekyll update
---
Welcome to this quick guide on how to set up a personal website using GitHub Pages and Jekyll. This guide is aimed at anyone who wants to create a simple, static website to showcase their work, blog, or just have a personal online presence.

Using GitHub Pages and Jekyll together is a great way to get started with web development as it requires no server-side processing and minimal setup. This guide will take you through the steps required to create and customize your own personal website using Jekyll and GitHub Pages.

Let's get started!

## Inintializing the Github repository

Create a new repository on GitHub with the name: `your-username.github.io` (replacing "your-username" with your actual GitHub username).

Clone the repository to your local machine using the command line:

## Installing Jekyll

Jekyll is a static site generator that is used to create the website files. It is written in Ruby and can be installed using the RubyGems package manager.

To install Jekyll, first install Ruby and RubyGems if you haven't already. Then, install Jekyll and Bundler using the following command:

```bash
gem install jekyll bundler
```

## Creating a new Jekyll site

To create a new Jekyll site, run the following command in the root directory of your GitHub repository:

```bash
jekyll new .
```

This will create a new Jekyll site in the current directory. The most important files and folders that were created are:

```bash
.
├── _config.yml
├── Gemfile
├── index.md
├── about.md
├── _posts
│   └── 2020-01-01-welcome-to-jekyll.markdown
└── _site
```

The `_config.yml` file contains the configuration data for your site. The `Gemfile` contains the gem dependencies for your site. The `index.md` file is the homepage for your site. The `about.md` file is an example page for your site. The `_posts` folder contains the blog posts for your site. The `_site` folder is where the generated site files will be placed when you build your site.

## Running the Jekyll site locally

To run your Jekyll site locally, run the following command in the root directory of your GitHub repository:

```bash
bundle exec jekyll serve
```

This will start a local web server and host your site at `http://localhost:4000`. Any changes you make to your site will be automatically reflected in the browser.

## Customizing your site

Now that you have a basic Jekyll site up and running, let's customize it to make it your own.

### Changing the site title

The site title is specified in the `_config.yml` file. Change the `title` field to the title you want to use for your site.

### Changing the site description

The site description is specified in the `_config.yml` file. Change the `description` field to the description you want to use for your site.

### Changing the site author

The site author is specified in the `_config.yml` file. Change the `author` field to the author you want to use for your site.

## Next steps

Now that you have a basic Jekyll site up and running, you can start customizing it to make it your own. Here are some ideas for things you can do to customize your site:

- Add your own content to the site
- Add your own CSS styles
- Add your own JavaScript scripts
- Add your own pages
- Add your own blog posts

## Resources

- [Jekyll documentation](https://jekyllrb.com/docs/)
- [Jekyll themes](https://jekyllthemes.io/)
- [Jekyll plugins](https://jekyllrb.com/docs/plugins/)
- [Jekyll tutorials](https://jekyllrb.com/docs/tutorials/)
- [Jekyll on GitHub Pages](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll)

## Credits

This guide was adapted from the [Jekyll documentation](https://jekyllrb.com/docs/).
Thanks to the Jekyll team for creating such a great tool!
If you have any questions or feedback, feel free to reach out to me using the contact information on my website!
