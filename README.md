TACC Latex Beamer Templates
===============

We currently need the libertine font so that we can be as close as possible to the original PowerPoint template. If you don't have it, you can install it like this:

wget http://mirrors.ctan.org/fonts/libertine.zip

unzip libertine.zip

cd ~/libertine/tex/latex

latex libertine.sty

sudo texhash

sudo updmap-sys
