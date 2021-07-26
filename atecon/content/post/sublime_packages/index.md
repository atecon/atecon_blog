---
title: "Recommended packages for the Sublime editor"
date: 2021-07-26T12:16:32+02:00
draft: false
type: post
description:
categories: [data, datscience]
tags: [sublime]
---

# Introduction
One and a half years ago I switched to the [Sublime editor as my favourite code editor](https://www.sublimetext.com/) (or IDE). For Python I used to use mainly IntelliJ but always thought that it feels too sluggish, slow and consumes rather massive memory. Also, I don't like its default key bindings (I know, everything can be set up here, too. But still...)

Furthermore, as I am a heavy [gretl](gretl.sourceforge.net/) user, I came across Sublime as it's relatively easy to write your own package for adding syntax support for a new language. My Sublime package named [Hansl-Gretl-Language](https://packagecontrol.io/packages/Hansl-Gretl-Language) is the result of this experiment.

I have to say that I also like Microsoft's open-source vscode software. It's support for Julia and Python is great, and many useful packages exist for it, too.

But this brief blog is supposed to list a few Sublime packages which I really recommend, and don't want to miss for daily work.

# My recommendations

## SideBarEnhancements
An absolute must-have is the ["SideBarEnhancements" package](https://packagecontrol.io/packages/SideBarEnhancements).

It enhances the functionality of the sidebar. It makes creating, copying, deleting and finding files and folders much easier. It's like adding functionalities of a good file explorer.

## Terminus
A proper IDE needs -- of course -- access to a terminal. In connection with the z-shell nothing will stop you! I always have a separate pane with multiple terminals open to boost productivity. [Terminus offers all you need.](https://packagecontrol.io/packages/Terminus)

## BracketHighlighter
When coding you have to deal with many nested brackets such [], (), {}, "", '', <tag></tag>, and even custom brackets. One easily gets lost with many brackets.

This package has *a single task* it properly fulfils: Alerting you if some bracket is not properly opened or closed. [You definitely need this.](https://packagecontrol.io/packages/BracketHighlighter)

## Origami
I love to work using multiple panes, and I really think a well-structured/ -orchestrated editor is fundamental to coding productivity. Apart from the side bar, my setting usually is:

```
  | 2
1 | -
  | 3
```

Hence, pane 1 occupies the left-hand half while panes 2 and 3 a vertically stacked.

[Origami easily allows you to create/ delete panes in any structure by clicking or through key bindings.](https://packagecontrol.io/packages/Origami)


## Pandoc
I frequently work with markdown files which I need to convert into html or pdf files. [Pandoc is a plugin that uses actual "Pandoc" to convert text from one markup format into another using just a few key strokes.](https://packagecontrol.io/packages/Pandoc)


## Pretty JSON
If you work with rather lengthy and nested json files, [this package is for you]( https://packagecontrol.io/packages/Pretty%20JSON). Just by a single key-stroke it re-formats a json file into a nice readable structure.


## Rainbow csv
If you have to deal with csv files, this simple tool is pretty cool and useful. It colourizes each column of a csv file by a different colour to make it much more readable to you. [I really love this package.](https://packagecontrol.io/packages/rainbow_csv)


## TodoReview
You might be also one of those people who add to-dos etc. to your code to highlight sections which need some additional refactoring or so. I frequently make use of `#TODO` and `#FIXME` flags.

If you have a large project with multiple files, one easily gets lost reminding or finding all the respective flags. The [TodoReview package is your friend](https://packagecontrol.io/packages/TodoReview). It scans your whole project for `#TODO`, `#FIXME` or user-defined keywords, and spits out a nice summary in which file and at which line you find the respective flag. I find this really useful.


That's it for the moment.






