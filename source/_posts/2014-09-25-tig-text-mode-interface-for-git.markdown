---
layout: post
title: "tig - text-mode interface for git"
date: 2014-09-25 15:12:25 +0800
comments: true
categories: tig, git
---
## What is Tig?

Tig is an ncurses-based text-mode interface for git. It functions mainly as a Git repository browser, but can also assist in staging changes for commit at chunk level and act as a pager for output from various Git commands.

## Installation
If you use OSX, you can easily use ``` homebrew ``` to install ```tig```, just run
```
brew install tig
```

## Usage
Just type ```tig``` under your project directory with ```git```
```
tig
```

![Alt text](https://raw.githubusercontent.com/chankaward/tig/master/ts-screenshoot.png "Optional title")


Check the current changed

```
tig status
```
* ```u``` to move the changed file to the ```staged```.
* ```!``` to discard file changed.
* ```D``` to delete untracked files.

![Alt text](https://raw.githubusercontent.com/chankaward/tig/master/tig-screenshoot.png "Optional title")

## Configuration
You can add a ```.tigrc``` file to your home directory for more custom configuration.

* Checkout my ```tigrc``` file on <a href="https://github.com/chankaward/.dotfile/blob/master/tigrc" target="_blank">Github</a>.

* Find the origin file on <a href="https://github.com/jonas/tig/blob/master/tigrc" target="_blank">https://github.com/jonas/tig/blob/master/tigrc</a>
