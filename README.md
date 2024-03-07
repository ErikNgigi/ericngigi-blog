# Mainroad Dark Theme

Mainroad Dark Theme is a customized version of the Mainroad theme for Hugo, designed with a dark mode aesthetic. It provides a sleek and modern look suitable for personal blogs, portfolios, or any content-focused websites.

## Installation

To use Mainroad Dark Theme in your Hugo project, you can clone this repository into your themes directory:

```
git clone https://github.com/example/mainroad-dark.git themes/mainroad-dark
```

Then, modify your `config.toml` file to set the theme:

```toml
theme = "mainroad-dark"
```

## Configuration

Below is an example `config.toml` file demonstrating the configuration options for Mainroad Dark Theme:

```toml
baseurl = "/"
title = "Mainroad"
languageCode = "en-us"
paginate = "10"
theme = "mainroad-dark"
disqusShortname = ""
googleAnalytics = ""

[Author]
  name = "John Doe"
  bio = "John Doe's true identity is unknown. Maybe he is a successful blogger or writer. Nobody knows it."
  avatar = "img/avatar.png"

[Params]
  subtitle = "Just another site"
  description = "John Doe's Personal blog about everything"
  opengraph = true
  twitter_cards = true
  readmore = false
  authorbox = true
  toc = true
  post_navigation = true
  postSections = ["post"]

[Params.sidebar]
  home = "right"
  list = "left"
  single = false
  widgets = ["search", "recent", "categories", "taglist", "social"]

[Params.widgets]
  recent_num = 5
  tags_counter = false

[Params.widgets.social]
  facebook = "username"
  twitter = "username"
  instagram = "username"
  linkedin = "username"
  telegram = "username"
  github = "username"
  gitlab = "username"
  bitbucket = "username"
  email = "example@example.com"
  google_plus = "profileid"
```

## Front Matter Example

You can configure individual pages using front matter. Here's an example:

```yaml
---
title: "Example article title"
date: "2017-08-21"
description: "Example article description"
thumbnail: "img/placeholder.jpg"
lead: "Example lead - highlighted near the title"
disable_comments: false
authorbox: true
toc: true
mathjax: true
categories:
  - "Category 1"
  - "Category 2"
tags:
  - "Test"
  - "Another test"
menu: main
---
```

For more information about front matter variables, refer to Hugo's official documentation.

## Sidebar

Mainroad Dark Theme features a configurable sidebar that can be positioned on the left, right, or disabled. You can adjust the layout in the `config.toml` file or individually for each page.

Widgets in the sidebar can be enabled or disabled based on your preferences. Additional widgets can be added by creating templates under `layouts/partials/widgets/<name>.html`.

## Menus

Mainroad Dark Theme supports multiple menus, including the main, side, and footer menus. You can add pages to menus by including a `menu` parameter in the page's front matter.

Please note that nested menus (submenus) are not supported in Mainroad Dark Theme.

## Contributing

Found a bug or have a feature idea? Feel free to open an issue or submit a pull [pull request](https://github.com/ErikNgigi/EricNgigi/pulls). Please follow the [contributing guide](contributing.md).

## License

This theme is released under the [GPLv2 license](https://github.com/ErikNgigi/EricNgigi/blob/master/LICENSE. Feel free to use and modify it according to your needs.
