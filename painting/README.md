# Painting

These are the files I generated to draw in the rf spectrum.

###### Much love Tommy Genesis :heart:

### What you need?

[GNU Radio](https://www.gnuradio.org/) and [gr-apint](https://github.com/drmpeg/gr-paint).

### How to use?

Convert your images to `.tga` and then convert then to `.bin` using the included `tgatoluma` tool (included in gr-paint). When you have the `.bin` file for your image just transmit it using `paint_tx` file (again, included in gr-paint).

#### Some notes

*-rev files are versions of the original image with a 180º rotation (reverse horizontal)
All test were done using GQRX.
