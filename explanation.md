This figure presents results of simulations and analysis from the paper "Two-dimensional wave propagation in layered periodic media", by Manuel Quezada de Luna and David I.  Ketcheson (submitted; pre-print available at http://arxiv.org/abs/1309.6666).  It shows how an initial Gaussian perturbation centered at the origin is propagated in a medium consisting of alternating horizontal layers of two different materials (the inset shows the structure of the medium).  The four central plots show the two-dimensional wave behavior, while the adjacent line plots show traces of the solution along the lines $x=0$ and $y=0$.

The top left plot shows the behavior in a homogeneous medium, consisting of an
expanding wavefront with no dispersion.  In the bottom left plot, the layers
have different impedances.  Waves propagating in the vertical direction
undergo repeated reflection and, as has been known for some time, exhibit
dispersion as a result.  This is evident in both the main color plot and in
the trace plot to the left, which show that a dispersive tail has developed.

The main subject of the paper is depicted in the top right plot, where the two layers have identical impedance, but different sound speeds.  In this case there is no reflection, but waves traveling horizontally undergo diffraction.  Remarkably, the large-scale effect of this diffraction is also that of dispersion, as seen in the horizontal trace above the plot.

Finally, the bottom right plot involves a medium in which both the impedance and the sound speed vary.  Effective dispersion is evident in both coordinate directions.  The reflective dispersion happens to be more pronounced in this case, but in general either effect can be dominant, depending on the material properties.

The main plots and the red traces are the results of finite volume simulations of the variable-coefficient acoustic wave equation -- with no dispersive terms.  In the paper, a high order "effective medium" dispersive wave equation is derived by formal homogenization techniques.  The black dotted lines are traces computed by solving these effective medium equations.  Excellent agreement is observed in all cases.

Finally, the small plots in the corners show the effective dispersion
relation, based on the effective medium equations.  The effective sound speed
is plotted as a function of the wavenumber components $k_x, k_y$.  The axes of
these plots are also oriented with the origin toward the center.  As suggested
by the central plots, it can be seen from the dispersion relations that
high-frequency waves always travel fastest in the horizontal direction.  But
for low-frequency waves, propagation in the vertical can be faster if there is
a large sound speed contrast and little or no impedance contrast.

Note that the straight horizontal lines that can be seen in some places are
the effect of the medium structure, and have nothing to do with grid
resolution, which is much too fine to be seen on the plot.
