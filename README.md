# Install

Run the following in order to install on the terminal
~~~ 
 cd ~
 git clone http://github.com/ibolmo/dotfiles.git cl
 source cl/etc/link
~~~

# dotfiles

This repo started out with just my . files (mainly vim files), but over time I've added to it, and now it represents a subset of all my command-line folders.

# File and directory structure

I store all my command-line files in a folder (cl), then under that folder there are 3 sub-folders (cl/bin cl/etc cl/doc), to keep them organized away from all my other files.  I link (etc/link) the dot files to the root of my home folder, so I prefer to store them without the . (gitignore rather than .gitignore), then I add the dot in the link.  So if you use one, make sure you put the dot back.

  * ~
  ** cl
  *** bin
  *** docs
  *** etc
  **** vim
          
## Warning

I mod these all the time, and sometimes I break stuff.  Also, my main platforms are OS X and Linux (Debian based) in the console, not XWindows.  Most of my stuff works just fine in something like gnome-terminal, but I usually only check my main platforms when I make changes.

## More information

[Blog post](http://blog.toddwerth.com/entries/9)
