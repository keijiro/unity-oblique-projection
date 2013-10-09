unity-cabinet-projection
========================

![screenshot]
(https://github.com/keijiro/unity-cabinet-projection/raw/gh-pages/screenshot.png)

This is a simple script which provides a cabinet projection (a kind of
[oblique projection](http://en.wikipedia.org/wiki/Oblique_projection))
matrix for an attached camera.

Usage
-----

1. Import CabinetProjection.cs.
1. Import CabinetProjectionEditor.cs into the “Editor” directory.
1. Attach CabinetProjection to a camera.

There are three parameters in CabinetProjection.

![inspector]
(https://github.com/keijiro/unity-cabinet-projection/raw/gh-pages/inspector.png)

- Angle: the angle of the third axis.
- Z Scale: the scale factor for the third axis.
- Z Offset: the offset along the third axis. You can use this to
  compensate the position of the camera along the third axis.

For a detailed example, see [the test branch]
(https://github.com/keijiro/unity-cabinet-projection/tree/test).
