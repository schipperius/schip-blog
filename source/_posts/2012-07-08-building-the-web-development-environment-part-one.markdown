---
layout: post
title: "Building the Web Development Environment - Part One"
date: 2012-07-08 09:37
comments: true
categories: [Development Environment]
draft: false
published: true
---

There are quite a few tools that need to be downloaded and or installed directly before you can begin building a website from scratch. The following list includes tools currently used and the order in which I installed them.<!-- more -->

We begin with a clean [install](/blog/2012/06/24/os-x-install/index.html) of OS X (Lion).

It took several iterations and a lot of reading to get this list, so if this is new to you, take your time and read the documentation (a few times if you have to) and have patience, installing one item at a time.

There is be a lot of new terminology and processes thrown at you, but it is all learnable, and if you make a mistake you can easily start again.

1. Web Browser - to browse the Web of course.
[Google Chrome](https://www.google.com/chrome) seems to be top of the hit parade these days.

	You may also want to install Mozilla's Firefox (you should already have Apple's Safari as part of the OS X install).

2. XCode - Apple's integrated development environment for creating applications. 

	But don't download the whole thing, just download the [Command Line Tools](https://developer.apple.com/downloads/index.action). 

	When the download is complete, open download folder, find `Command Line Tools.mpkg`, double click to install and follow the prompts.

3. Command Line Interface (CLI) - is used to interact directly with the computer.
[iTerm2](http://www.iterm2.com/) is a replacement for the default Terminal that ships with your Mac.

4. [Homebrew](http://mxcl.github.com/homebrew/) - is a package management system that easily installs additional tools you will need. 

	To install Homebrew, open an iterm2 window and copy/paste: `ruby <(curl -fsSkL raw.github.com/mxcl/homebrew/go)` at the Terminal prompt. 

	Read the documentation on the [Homebrew](http://mxcl.github.com/homebrew/) site for more information.

5. Wget - is a computer program that retrieves content from web servers. This can be installed in a terminal window with Homebrew: `$ brew install wget`

6. [Oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) - is a community-driven framework for managing the zsh configuration. 

	Oh-my-zsh can be installed in a terminal window with wget: `wget --no-check-certificate https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh`

This concludes part one of a multi-post article on setting up your environment to begin building websites. The second part will include installing version control, a database, image editor and more...