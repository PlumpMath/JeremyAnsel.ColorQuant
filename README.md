JeremyAnsel.ColorQuant
======================
[![Build status](https://ci.appveyor.com/api/projects/status/u39upbktebxs5hwn?svg=true)](https://ci.appveyor.com/project/JeremyAnsel/jeremyansel-colorquant)

JeremyAnsel.ColorQuant is a C# implementation of the Xiaolin Wu's Color Quantizer (v. 2).

C Implementation of Xiaolin Wu's Color Quantizer (v. 2) (see Graphics Gems volume II, pages 126-133) : http://www.ece.mcmaster.ca/~xwu/cq.c.

Algorithm: Greedy orthogonal bipartition of RGB space for variance minimization aided by inclusion-exclusion tricks. For speed no nearest neighbor search is done. Slightly better performance can be expected by more sophisticated but more expensive versions.
