# WebGL-Mali-400-blend-bug

This repository presents a demo bug on Mali-400.

Reproduced: mobile Chrome.
Description: in some frames the transparent objects are rendered on top of the opaque objects, when the transparent objects are behind the opaque objects.

Used: glMatrix (https://github.com/toji/gl-matrix)