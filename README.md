CPH GOPHER
==========

Original gopher by Renée French, re-imagined by Søren Siebuhr and then
vectorized in Inkscape.

Notes
-----

Converting png output from Inkscape to a square image:

    gm convert source.png -thumbnail '1150x1150>' -background transparent -gravity center -extent 1150x1150 new.png

Finally, tidy up with `pngquant` and `pngcrush`.

License
-------

Creative Commons Attribution 3.0
