TheUnixZoo: Vim Colour Scheme
=============================

Easy on the eye Vim themes for long hacking sessions.

What is This?
-------------

This is my vim colour scheme for gvim and 16-colour terminals. Well,
actually it is two themes.  Both are designed to be minimal,
non-intrusive and easy on the eye. I believe that a common mistake to
bombard the user with too many different colours, thus inducing a
psychedelic headache.

Installation
------------

* Copy theunixzoo.vim to ~/.vim/colors
* Open vim or gvim and type in command mode: `:colors theunixzoo`

The Colour Schemes
------------------

###GVim:

The gvim theme is designed for indoor use. Since we have 24-bit
colour at our disposal, the colours for the GUI are not limited and I
am able to give you rich autumn colours.

![Gvim colour scheme](https://raw.github.com/vext01/theunixzoo-vim-colorscheme/master/gvim.png)
  
###16-Colour Terminal:

The cterm (16-bit color terminal) theme was designed so as to work
both indoors and out. By this I mean it will not suffer from contrast
issues if you are using xterm with:

* Black text on a white background (ie. default xterm settings).
* White (or light gray) text on a black background.
 
If you want the latter put this in your ~/.Xdefaults:

```
xterm*background: black                                                         
xterm*foreground: gray60
```
  
The cterm theme will work on a standard PC terminal just fine (sometimes
I don't start X). I have not tried it on a Sun terminal or anything exotic.

![Terminal colour scheme](https://raw.github.com/vext01/theunixzoo-vim-colorscheme/master/cterm.png)
  
Donate
------

I offer you this for free under an ISC license! Free! Free! Free!

If you like this, please help a broke PhD student and donate a pint of
English ale. Donate via PayPal to  vext01 (at) gmail (dot) com. Thanks.
