unity-oblique-projection
========================

![screenshot](https://github.com/keijiro/unity-oblique-projection/raw/gh-pages/screenshot.png)

This is a C# script which provides [an oblique projection matrix](http://en.wikipedia.org/wiki/Oblique_projection) for an attached camera.

Usage
-----

1. Import ObliqueProjection.cs.
1. Import ObliqueProjectionEditor.cs into the “Editor” directory.
1. Attach ObliqueProjection to a camera.

There are three parameters in ObliqueProjection.

![inspector](https://github.com/keijiro/unity-oblique-projection/raw/gh-pages/inspector.png)

- Angle: the angle of the third axis.
- Z Scale: the scale factor for the third axis.
- Z Offset: the offset along the third axis. You can use this to
  compensate the position of the camera along the third axis.

For a detailed example, see [the test branch](https://github.com/keijiro/unity-oblique-projection/tree/test).
