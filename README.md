# Hexo-material

Material design theme for [Hexo], made with materializeCSS, [Preview](http://fabiangutierrez.co/notes)
![Hexo-material preview](https://lh3.googleusercontent.com/0FEdLGHgdQGLt1UweiB-nHxDX77xsOXRWsngLoYEorZMeQ7Bq7MfAjiCsG3HHYZC8b2WXC_f53A4oFz2i3NABOJjRzYpnrDzrFN9FzHyIFmqcm4gIkRwhxJJXwJTXs9GfapyvtMRH0in7RNPIFJUQXBGc1JEYCmekf1GH_KCB30U-k9kSYue-40QXr3wplG-Y03Z633vKEL49w7HkKNbM6XT4GBi2e5On5A3VuivElWhiNCtBbD9QhdV4KI8QkXVlviPGILSoJBkit2XcoUtEaFZXBnf6Fw-udllaPnaYPDYOJ6PTu8WJ2_S_cMQY2Rr8-k8JoR_BtfE-H2y9n7u5B--OAENg-YaoSv3e0TWSkSdQjmQ78GFMTnCR6nqfR94IqeaGWFjnJchprBaNvjWQEZ9o6yLL7TQS_C4nFDrXtmBJHP-OkifDQIVlGlU9ok6tx19t5ERvqvC26NdR811Adyocn0naDBX5ioZ8XK7LXaKq2ezhdP3vPBNaESoKOmW3-f3VLcETURiihpQoyO9comBQLEZftksI7JW7u5gu0S2AKr3txHPrYXQAlIR1lbe8-dUf8FE75om6S45xAZ2rX4FvJQap3-bdTM6t6lk93fIluUD96AZuX0YPAxtEA-w6OGq8rLdCBEE8zyV4JDdEcrTaylNg5ZThRXorC70sHU=w627-h312-no)
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
