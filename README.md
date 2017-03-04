# Hexo-material

Material design theme for [Hexo], made with materializeCSS, [Preview](http://fabiangutierrez.co/notes)

![Hexo-material light theme preview](https://lh3.googleusercontent.com/legL7BP_mttHYHkWPu-6hN1UekEKe5FwmkJGlqrma1GO00WhKfDoedz6kCw4F4RapynOIAbUE56MOBtA7Yga7Deej4OrbGBteggyaKtvd1tjR69W_GraHp3oSvOAkHQyZ53gTbmJWXLK1BUTnMQc-ccQeQwYaigPxtRpXw0BcaQ25zMOUBpCLrXTnyN2d517KoQEB8rRHpKEZ03yPXmyFDiA7zAlDm9t6nlp_5OaROK2P3rlQz4oVX1Z3I09cYw3IW0Y57H391VcRiKkFoy4xzLJMX7ne63miALqsE8_Ho9UCGcZn0ZK0t69vimRUTQPvsGbteS6B3GtqVK9flnFPD4TVCdP-N4a022l3pEKZuC1xtBCIHSb60j7ZiE9TSuxO829x9TPX-AlvdW59FxPTtVxXqCAaI5BczsyCbsOKVmpgzacORpBQaNVUHQt2Rsgl_hD66yFZK9XpCuaR-JRrDl3x-YYTunSmQwjWjYbTMAPd5N9db_wN1XpOvOTKH6s5fYfcuKEIkzCj0lyoYbOLrCZ1n4D-dd-M-sDw7f9fMY4KNDRWFFI0yOdkge9PKAN6xC-SIOa4h30FK2tr9FSO415w0YBt5ANSFoiNDcr0jJ1RNIjVGp3DqnNjsDWaDO7vZ1ZaqbQn1R5wj-PBaGrukcyOGPaB6io7PfJ4aVXXf0=w1358-h676-no)

![Hexo-material dark theme preview](https://lh3.googleusercontent.com/fwFsUufoyuxXrbrw8T0nwofluMThhq-Sc5oHfQbuMYmL2LVrD2g80JXa-3pz4X4tsmoZLPwYqcvjinM8hz0lBH7G8qBQaEn7x-wgJ4_NEUX7h5j4NzxLc-A3gsDpEj9f98VHdcd8bXzaVqTP5MXisjS9M2tghKEKESfiUaQYOo7XbmE1oUTYX2DN5JUqIAcUdwBVqqEWuuwnZkDvmeboO-ths0t7_o8qM6GaCecEf-fKy87UpQztgJKP5XadaU_EFogiWFyaYZ4fp16-qnx0ygNdt5WFNMes30zrPKzCT9CBhyIqXX61CFo9m8cPvDPDMh8IOCcYjLvEqTgzWWCPnEx8wtqqw-iuDipdDH2Ax9Syx2DcgAQGYPQouwfnHX_wjF_FDk7smgXgvwmHWzsXNw44kxf_hJsPzoiWr6Pozmhgc3CWlzlDZK_ulYYKJWv1GxGKiDMpcer0sfJNCRLHFzaOSCC-JILC5x280hxjyNFg6gUSeYf45WkPHr74EIxN-6YKlSC6UEsOjNWTw0aY2_-QdWMLflKG-mjxPIoBx67OygHwNfMe7tRjmWPvSDcTRfwkHesAslBMsQXyr0oOe37si4Mv1rWigDWWm-ulrIxYaGFsx2JcTTCdZ-xUePSBo7fj2UVmww1kkp5ss7vzA9oRpz9-zKpd2fOyotwr_x8=w1350-h667-no)

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
