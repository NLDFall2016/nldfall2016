---
title: "Running MATLAB in a terminal"
author: "Rachael Steiner"
date: "2016"
license: "MIT License"
---

# Running MATLAB in your terminal

(This specifically applies to Linux, but might also work for Mac and possibly Windows.)

This will allow you to write your MATLAB code in your text editor of choice, and
  run it in a terminal, without opening the MATLAB IDE. Note that you do still
  need to have MATLAB installed on your computer.

## Starting MATLAB

To start an interactive MATLAB session without the IDE, first open a terminal.

`cd` into your project folder.

Enter `matlab -nodesktop`

## An alternative editor

If you're looking for an editor to use, I recommend [atom](http://atom.io). It's
  highly customizeable with a lot of add-ons to add to the functionality (such
  as syntax highlighting and the ability to run a terminal in the same window).

### Syntax highlighting

Install the package [language-matlab](https://atom.io/packages/language-matlab)
  to get syntax highlighting for MATLAB.

### Run a terminal within Atom

Atom has a few packages that let you run a terminal from within the editor. The
  most popular one is [terminal-plus](https://atom.io/packages/terminal-plus),
  but if it is buggy, you could try one of its forks:
  [terminal-fusion](https://atom.io/packages/terminal-fusion) for Linux, or
  [platformio-ide-terminal](https://atom.io/packages/platformio-ide-terminal) for
  Windows and Mac. If you only or primarily plan on using it for MATLAB,
  you could go to the package's options and enter `matlab -nodesktop` for the
  "Auto Run Commands" option, which will make it start MATLAB automatically.

There is also [script](https://atom.io/packages/script), which
  allows you to run code directly from the editor.
