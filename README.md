bootstrap_MockupTheme
=====================

a bootstrap theme that will make your site look more like a prototype.

Possibly useful if you want to show some ideas which you directly prototyped in code. Using a theme which shows that the design is preliminary may get you around »I dont like this color« and »can we change this font to…«-discussions so you can focus on more general things like determining if the site needs a prominent login or a sidebar etc.

setup
-----
1.) clone this repo

2.) download Bootstrap from http://getbootstrap.com

3.) in the bootstrap_MockupTheme file `mockupTheme-bootstrap.less` set the path to the `/less/bootstrap.less` (first line) 
and `/less/utilities.less` (last line) files of bootstrap. (the current paths work out of the box, if you place the repo’s files 
in a new folder in bootstraps root folder (the one with `README.md` and the `LICENSE` in) 

4.) open a terminal, navigate to the folder you put this repo (bootstrap_MockupTheme) in and run `lessc custom-bootstrap.less bootstrap.css`

The resulting `css` file is created from the standard bootstrap files and has the MockupTheme customizations baked in. 

example
-------

![example](example.png)
