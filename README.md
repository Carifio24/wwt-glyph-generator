# wwt-glyph-generator

This is a small Python script to generate text spritesheet images for [WorldWide Telescope](http://worldwidetelescope.org/home),
as well as associated XML files instructing the WWT renderer about the locations of the various glyphs on each image.

## Usage

To create the glyph files, simply install the package requirements in your environment and run the script:

```python
python make_glyphs.py
```

Running without arguments, as above, will generate glyph files tagged as version 2, in a `docs` subdirectory of the current
directory. If desired, one can adjust the version number, output directory, and characters used via command-line arguments.
