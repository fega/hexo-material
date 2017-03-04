# Hexo-material

Material design theme for [Hexo], made with materializeCSS, [Preview](http://fabiangutierrez.co/notes)

## Installation

### Install

``` bash
$ git clone git clone https://github.com/fega/hexo-material.git
```

**Hexo-material requires Hexo 2.4 and above.**

### Enable

Modify `theme` setting in `_config.yml` to `hexo-material`.

### Update

``` bash
cd themes/hexo-material
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archives
- recent_posts

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **sidebar** - Sidebar style. You can choose `left`, `right`, `bottom` or `false`.
- **widgets** - Widgets displaying in sidebar
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID

## Development

### Requirements

- [Grunt] 0.4+
- Hexo 2.4+

[Hexo]: http://zespia.tw/hexo/
[Grunt]: http://gruntjs.com/
