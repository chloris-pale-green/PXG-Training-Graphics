# PXG-Training-Graphics

Graphics used in training missions for [Phoenix Group](https://pxg-arma.github.io/).

Graphics should be in SVG format and created with [Inkscape](https://inkscape.org/).


## Dependencies

- Fonts: [Philosopher](https://fonts.google.com/specimen/Philosopher), [PT Sans](https://fonts.google.com/specimen/PT+Sans)


## How to use in missions

1. Export the graphics as a 1920x1080 px JPEG.
2. Use [TinyJPG](https://tinyjpg.com/) to make the files significantly smaller.
3. Copy the optimized JPEG file into the mission directory.
4. Edit attributes of a billboard or a similar object. Find the `Texture` field. Enter the path to the JPEG file relative to the mission directory. Use backslash as the directory separator.
