# BlackDocPlus (GitHub Page)

![Jekyll version](https://img.shields.io/badge/Jekyll-3.x-brightgreen.svg?style=flat-square)

* View Demo: [BlackDocPlus](https://robert-zacchigna.github.io/BlackDocPlus/)
* View the Original Theme: [BlackDoc](https://robert-zacchigna.github.io/BlackDoc)

To run this site locally, use the [local](https://github.com/Robert-Zacchigna/BlackDocPlus/tree/local) branch

BlackDoc is a two-column [Jekyll](http://jekyllrb.com) theme that's ideal for websites that require a master-detail 
layout for viewing of content. It's based on [Poole](http://getpoole.com), the Jekyll butler, and the [Hyde](http://hyde.getpoole.com) theme.

![BlackDoc screenshot](https://raw.githubusercontent.com/karloespiritu/blackdoc/master/public/images/blackdoc-screenshot.jpg)

## Contents

- [Features](#features)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Options](#options)
  - [Sidebar menu](#sidebar-menu)
  - [Scrolling sidebar content](#scrolling-sidebar-content)
  - [Themes](#themes)
- [Development](#development)
- [Author](#author)
- [License](#license)

## Features

* Now compatible with Jekyll 3.x
* Two-column layout with scrolling sidebar content
* Ideal for websites that require  master-detail view of content

## Quick Start

Download the zip file or clone the BlackDoc repo.

```bash
$ git clone git@github.com:karloespiritu/BlackDoc.git mysite
$ cd mysite
```
Make sure you have Ruby 3.1.2 or higher installed.

```bash
$ ruby --version
ruby 3.2.1
```

Install bundler and install dependencies.

```bash
$ gem install bundler
$ gem install jekyll bundler
$ bundle install
$ bundle update --bundler
```

Build and run your BlackDoc site.

```bash
$ bundle exec jekyll serve
```

>**NOTE:** Use the [local](https://github.com/Robert-Zacchigna/BlackDocPlus/tree/local) branch if you want to build this 
> site locally, this version is only for running the site through GitHub Pages.

## Usage

BlackDoc is a theme built on top of [Poole](https://github.com/poole/poole), which provides a fully furnished Jekyll 
setup—just download and start the Jekyll server. See [the Poole usage guidelines](https://github.com/poole/poole#usage) 
for how to install and use Jekyll.


## Options

BlackDoc includes some customizable options, typically applied via classes on the `<body>` element.


### Sidebar menu

Create a list of nav links in the sidebar by assigning each Jekyll page the correct layout in the page's 
[front-matter](http://jekyllrb.com/docs/frontmatter/).

```
---
layout: page
title: About
---
```

**Why require a specific layout?** Jekyll will return *all* pages, including the `atom.xml`, and with an alphabetical 
sort order. To ensure the first link is *Home*, we exclude the `index.html` page from this list by specifying the `page` layout.


### Scrolling sidebar content

By default, BlackDoc includes a scrolling sidebar that will display your markdown files in alphabetical order.

### Themes

BlackDoc ships with eight optional themes based on the [base16 color scheme](https://github.com/chriskempson/base16). 
Apply a theme to change the color scheme (mostly applies to sidebar and links).

To use a theme, add anyone of the available theme classes to the `<body>` element in the `default.html` layout, like so:

```html
<body class="theme-base-08">
  ...
</body>
```

To create your own theme, look to the Themes' section of [included CSS file](https://github.com/Robert-Zacchigna/blackdocplus/blob/master/public/css/blackdoc.css). 
Copy any existing theme (they're only a few lines of CSS), rename it, and change the provided colors.

## Original Theme Author

**Karlo Espiritu**
- <https://github.com/karloespiritu>
- <https://twitter.com/karloespiritu>

## Theme Modification By

**Robert Zacchigna**
- <https://github.com/Robert-Zacchigna>

## License

Open sourced under the [MIT license](LICENSE.md).
