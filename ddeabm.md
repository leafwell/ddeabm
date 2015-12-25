project: ddeabm
project_dir: ./src
output_dir: ./doc
project_github: https://github.com/jacobwilliams/ddeabm
summary: Modern Fortran implementation of the DDEABM Adams-Bashforth algorithm
author: Jacob Williams
github: https://github.com/jacobwilliams
predocmark_alt: >
predocmark: <
docmark_alt:
docmark: !
display: public
display: private
display: protected
source: true
exclude: pyplot_module.f90
graph: true

Brief description
---------------

This is a modern object-oriented Fortran implementation of the DDEABM Adams-Bashforth ODE solver. The original Fortran 77 code is public domain, and was obtained from the [SLATEC library](http://www.netlib.org/slatec/src/). It has been extensively refactored.

This project is hosted on GitHub at: https://github.com/jacobwilliams/ddeabm

## References

1. L. F. Shampine, M. K. Gordon, "Solving ordinary differential equations with ODE, STEP, and INTERP",  Report SLA-73-1060, Sandia Laboratories, 1973.
2. L. F. Shampine, M. K. Gordon, "Computer solution of ordinary differential equations, the initial value problem", W. H. Freeman and Company, 1975.
3. L. F. Shampine, H. A. Watts, "DEPAC - Design of a user oriented package of ode solvers", Report SAND79-2374, Sandia Laboratories, 1979.
4. H. A. Watts, "A smoother interpolant for DE/STEP, INTRP and DEABM: II", Report SAND84-0293, Sandia Laboratories, 1984.
5. R. P. Brent, "[An algorithm with guaranteed convergence for finding a zero of a function](http://maths-people.anu.edu.au/~brent/pd/rpb005.pdf)", The Computer Journal, Vol 14, No. 4., 1971.
6. R. P. Brent, "[Algorithms for minimization without derivatives](http://maths-people.anu.edu.au/~brent/pub/pub011.html)", Prentice-Hall, Inc., 1973.

# License

The ddeabm source code and related files and documentation are distributed under a permissive free software [license](https://github.com/jacobwilliams/ddeabm/blob/master/LICENSE) (BSD-style).  The original DDEABM Fortran 77 code is [public domain](http://www.netlib.org/slatec/guide).