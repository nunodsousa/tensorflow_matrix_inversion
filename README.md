# Tensorflow Matrix Inversion

The evaluation of the inverse of a matrix is very common problem in science. Examples can be easily found in all subfields of physics, such as electrodynamics[1] or phase transitions[2].

Until know the vast majority of the calculations where made in CPUs. However in the last decade the GPUs get into the scene, due to a significant efford of hardware companies to adapt their hardware to scientific computation.
The goal of this notebook is to show how to compute the inverse of a random complex matrix using tensorflow.

[1] 'Magneto-Optical Activity in High Index Dielectric Nanoantennas', N. De Sousa, L.S. Froufe-Pérez, J.J. Sáenz, A. García-Martín, Sci. Rep. 6 (2016)

[2] 'Effect of long range spatial correlations on the lifetime statistics of an emitter in a two-dimensional disordered lattice' N. de Sousa, J.J. Sáenz, A. García-Martín, L.S. Froufe-Pérez, M.I. Marqués, Phys. Rev. A 89, 063830 (2016)
