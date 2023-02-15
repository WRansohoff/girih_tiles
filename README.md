# Girih Tile SVGs

Girih is a form of decorative geometry which likely started around 1200CE, and grew in popularity and complexity over the following centuries.

This repository contains digital representations of each tile, with their dimensions set by fully constrained CAD sketches. These sketches can be opened and edited using [FreeCAD](https://www.freecad.org/).

The SVG files produced from the CAD drawings should be precise enough to simulate very large digital designs in vector image editors, without accumulating errors as the design grows.

Each tile's dimensions are set such that each edge is 10mm in length. You can scale them to whatever size you want, but be sure to use the same scaling ratio for each tile if you want them to fit together.

I have tried to reproduce and verify the tile shapes as best I can, but I'm not an expert and there may be mistakes. Corrections are welcome.

# Tiles

## Torange

![Torange](torange/torange.svg)

## Pange

![Pange](pange/pange.svg)

## Tabl

![Tabl](tabl/tabl.svg)

## Shesh Band

![Shesh Band](shesh_band/shesh_band.svg)

## Sormeh Dan

![Sormeh Dan](sormeh_dan/sormeh_dan.svg)

# Future Work

I would like to add the extended sets of tiles and adapters described in Eriksson, 2021.

The FreeCAD sketches are sort of messy because I don't know how to move angle constraints, and FreeCAD sometimes puts them in odd places.

I might be able to make drawings which do a better job of highlighting the important angles and features if I can learn more about the underlying theory. I'd like to find a copy of "Islamic Geometric Patterns: Their Historical Development and Traditional Methods of Construction" by Jay Bonner.

# References

[Lu, Peter J., & Steinhardt, Paul J. (23 Feb 2007). Decagonal and Quasi-Crystalline Tilings in Medieval Islamic Architecture. Science. 315, 1106-1110](https://doi.org/10.1126/science.1135491)

[Eriksson, Lars (26 Jul 2021). The Short Tiles Category. Bridges 2021 Virtual Conference.](https://www.researchgate.net/publication/353444031_The_Short_Tiles_Category)

[Kuhn, Oliver (Sep 2014). Science Break: The Math of Mosaics. CSEG Recorder. Vol. 39 No. 07](https://csegrecorder.com/columns/view/science-break-201409)
