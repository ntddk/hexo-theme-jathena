# hexo-theme-jathena

A Japanese theme for [hexo](http://hexo.io/), modify from Hexo [athena](https://github.com/steven5538/hexo-theme-athena) theme.

[Preview](http://ntddk.github.io)

## Installation

### Install

``` bash
$ git clone https://github.com/ntddk/hexo-theme-jathena.git themes/jathena
```

### Enable

Modify `theme` setting in `_config.yml` to `jathena`.

### Update

``` bash
cd theme/jathena
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
  About: /about
# Header Icon
menu_icon:
  Home: nav-home-icon
  Archives: nav-archives-icon
  About: nav-about-icon

rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
```

- **menu** - Navigation menu, you need to `hexo new page 'about'` for the about page.
- **menu_icon** - Navigation icon
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
