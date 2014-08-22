CPH GOPHER
==========

Original mascot by Rene French, re-imagined by Søren Siebuhr and vectorized my
Morten Siebuhr.

Notes
-----

Converting png output from Inkscape to a square image, padded with white:

    gm convert source.png -thumbnail '1150x1150>' -background transparent -gravity center -extent 1150x1150 new.png

Finally, tidy up with `pngquant` or such.


