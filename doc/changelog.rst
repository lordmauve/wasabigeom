Changelog
=========

2.1.1 - released 2022-04-20
---------------------------

* Fix package compatibility with Python 3.10

2.1.0 - released 2021-09-24
---------------------------

* New: add :class:`wasabigeom.Transform` for 2D affine transformations.
* Add vec2.from_polar() static method.
* Can construct from any 2-sequence of floats


2.0.1 - released 2020-09-27
---------------------------

* Several bugfixes, particularly around multiplying/dividing by `int` and
  `nonvec + vec`


2.0.0 - released 2020-09-25
---------------------------

* Breaking Change: module name changed from ``wasabi.geom`` to ``wasabigeom``
* Breaking Change: ``Vector`` class renamed to ``wasabigeom.vec2``
* Breaking Change: ``vec2.angle()`` and other functions now return radians.
* New: :func:`wasabigeom.bresenham()`
* New: Cythonised the sources; hand-optimised ``vec2``


0.1.3 - released 2012ish
------------------------

* Original, pure-Python release
