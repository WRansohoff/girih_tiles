# Girih Tile SVGs

Girih is a form of decorative geometry which likely started around 1200CE, and grew in popularity and complexity over the following centuries.

This repository contains digital representations of each tile, with their dimensions set by fully constrained CAD sketches. These sketches can be opened and edited using [FreeCAD](https://www.freecad.org/).

The SVG files produced from the CAD drawings should be precise enough to simulate very large digital designs in vector image editors, without accumulating errors as the design grows.

Each tile's dimensions are set such that each edge is 10mm in length. You can scale them to whatever size you want, but be sure to use the same scaling ratio for each tile if you want them to fit together.

I have tried to reproduce and verify the tile shapes as best I can, but I'm not an expert and there may be mistakes. Corrections are welcome.

# Tiles

## Torange

![Torange](torange/torange.svg)
![Torange with straps](torange/torange_straps.svg)

## Pange

![Pange](pange/pange.svg)
![Pange with straps](pange/pange_straps.svg)

## Tabl

![Tabl](tabl/tabl.svg)
![Tabl with straps](tabl/tabl_straps.svg)

## Shesh Band

![Shesh Band](shesh_band/shesh_band.svg)
![Shesh Band with straps](shesh_band/shesh_band_straps.svg)

## Sormeh Dan

![Sormeh Dan](sormeh_dan/sormeh_dan.svg)
![Sormeh Dan with straps](sormeh_dan/sormeh_dan_straps.svg)

# Troubleshooting

The latest version of FreeCAD (v0.20.2) may not render angle constraints in the correct location on Windows.

[The FreeCAD team appears to be aware of the issue,](https://github.com/FreeCAD/FreeCAD/issues/8220) so it should be addressed in a future release. For now, you may be able to use the [slightly older v0.20.1 release](https://github.com/FreeCAD/FreeCAD/releases/tag/0.20.1) if the CAD drawings do not render correctly.

# Future Work

I would like to add the extended sets of tiles and adapters described in Eriksson, 2021.

The renders with straps only have a single 'layer'. It might be nice to add versions with overlapping straps, as depicted in Zheng & Aslaksen, Figure 3.

I might be able to make drawings which do a better job of highlighting important dimensions if I can learn more about the underlying theory. I'd like to find a copy of "Islamic Geometric Patterns: Their Historical Development and Traditional Methods of Construction" by Jay Bonner.

# References

[Lu, Peter J., & Steinhardt, Paul J. (23 Feb 2007). Decagonal and Quasi-Crystalline Tilings in Medieval Islamic Architecture. Science. 315, 1106-1110](https://doi.org/10.1126/science.1135491)

[Eriksson, Lars (26 Jul 2021). The Short Tiles Category. Bridges 2021 Virtual Conference.](https://www.researchgate.net/publication/353444031_The_Short_Tiles_Category)

[Kuhn, Oliver (Sep 2014). Science Break: The Math of Mosaics. CSEG Recorder. Vol. 39 No. 07](https://csegrecorder.com/columns/view/science-break-201409)

[Zheng, Ser & Aslaksen, Helmer (2008). Quasi-Periodicity in Medieval and Islamic architecture and ornament.](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=5c7929544b6595d58bbc418fad849d9ee8f16e21)
