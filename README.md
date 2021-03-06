# renderer

A python-based renderer for stl files and generic 3D objects. This script takes a generic .stl file, reads it and parses it into triangles, and then projects the triangles onto a viewing screen, computing intersections and overlaps, and applies shading as appropriate.

![teapot.png](https://raw.githubusercontent.com/ja3067/python-stl-renderer/master/examples/example.png)

## Usage

To run the script, simple clone the repository and run

```
python render.py [myfile.stl]
```

where myfile.stl is your favorite stl file. The library provides an example teapot stl file in the examples folder, so you can run

```
python render.py examples/teapot.stl
```

to generate a plot and save it to the directory.

## Dependencies

This script depends on matplotlib, numpy, and the stl python libraries. To install these, run

```
pip install matplotlib numpy stl
```

from a command line.
