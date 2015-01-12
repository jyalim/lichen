lichen
======

Lichen is configured to handle 256 color terminals. 
Many of the colorschemes that can be found online are actually designed
  for gViM, which is the GUI implementation of ViM.
Lichen will provide a similar syntax highlighting experience as gViM
  but inside a terminal.
It also has most of the relevant keywords for configuring any new/old 
  colorscheme, so it provides as a good template for a new 256-terminal
  colorscheme.


Lichen was modified from a colorscheme called moss, which partially 
  worked in the terminal.
Lichen provides a dark colorscheme with blues, greens, and browns
  designed to minimize distraction and eyestrain from brightness
  while maximizing utility by providing quick distinct color shorthands.
Reds and oranges are resolved for searching, error handling, and errors.


Lichen has been tested with nearly every programming language/format 
  including TeX (LaTeX), Python, Fortran, Fortran 90, C, C++, vimscript, 
  PERL, bash, csh, yaml, json, html, xml, md (markdown), MATLAB, 
  sed, and even binary.
The vimrc found in http://github.com/hellabyte/myconfig is recommended 
  to get syntax highlighting working for all the above filetypes (i.e. 
  for Fortran 90 the Hellabyte vimrc will correctly provide free-format
  syntax highlighting).


Lichen has been tested on a variety of platforms, including Ubuntu,
  Arch Linux, CentOS, Redhat, and Mac OS X.
It has also been tested successfully in a variety of terminals including
  Terminal.app, iTerm2.app, Gnome Terminal, Terminator, xterm, and 
  rxvt-unicode (urxvt).
The most important setting is that the environment variable 
  `TERM' is set to 256 colors (although 88 colors works too).


To install, use your favorite plugin manager or just use `cp` after 
  cloning--just make sure that `lichen.vim` ends up in the 
  correct directory: `$HOME/.vim/colors`.


![ViM Colors Example](http://i.imgur.com/OcdU5F0.png)
![Comment Color Example](http://i.imgur.com/IoSFMeb.png)


(C) 2014 - 12 - 23 -- Nathaniel Hellabyte
