CLINews
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

### Read news:
`./news`

### List all added sources:
`./news -l`

### Add new (RSS) source:
`./news -a <rss-url>`

### Remove exists (RSS) source:
`./news -r <rss-url>`

### Display help:
`./news -h`

## Todo: 
- Themes support
- Unicode support
- Strip HTML encoded strings in articles content
