# Splines

Small Julia library for splines that are expanded in B-splines.

Features:
- Generation of B-splines of arbitrary order given a knot sequence
- Generation of some common knot sequences
- Differentiation of B-splines and generation of matrix for
  differentiation of splines.
- Utility to generate Gauß–Legendre points/weights for Gauß quadrature
  for splines. Depends on [FastGaussQuadrature](https://github.com/ajt60gaibb/FastGaussQuadrature.jl).

The tests implemented so far are purely graphical and need visual
confirmation.

[![Build Status](https://travis-ci.org/jagot/Splines.jl.svg?branch=master)](https://travis-ci.org/jagot/Splines.jl)
