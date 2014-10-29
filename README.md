CLInews
=======

News reader for hackers, geek, and command-line fanatics =]] written in Python

![clinews](http://i.imgur.com/Dli4JHW.png)

## Features:
- Manage (show/add/delete) source list
- List news from sources (RSS)
- Go to articles URL
- Working completely in command line
- Can be used in IDEs (WebStorm, PyCharm, Eclipse,...)

## Installation:

Clone this repository to your computer. Run this command:

`chmod +x news`

## Usage:

#### Read news:
`./news`

Press UP/DOWN to switch articles.

Press SPACE to open current article in browser.

#### List all added sources:
`./news -l`

#### Add new (RSS) source:
`./news -a <rss-url>`

#### Remove exists (RSS) source:
`./news -r <rss-url>`

#### Display help:
`./news -h`

## Libraries used:
- [Rainbow Stream](https://github.com/DTVD/rainbowstream)'s colors.py
- [Universal Feed Parser](https://pypi.python.org/pypi/feedparser)


## Todo: 
- Create setup script
- Themes support
- Unicode support
- Strip HTML encoded strings in articles content
