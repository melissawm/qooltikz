# qooltikz
Sample of `qool` stuff to do with TikZ.

These examples use https://github.com/mkrphys/ipython-tikzmagic

## Some execution notes

1. Install `pdflatex` (including TikZ - this is usually done by installing TeXLive).
2. Install `pdf2svg` using your OS package manager.
3. The ipython tikzmagic uses ImageMagick `convert` to generate the figures. Due to a security policy by ImageMagick, you must use the 
```
%%tikz -f svg
```
magic to actually see the generated outputs (see https://github.com/mkrphys/ipython-tikzmagic/issues/32)
