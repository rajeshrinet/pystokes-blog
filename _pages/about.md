---
layout: page
title: About
permalink: /about/
---
![Imagel](https://raw.githubusercontent.com/rajeshrinet/pystokes/master/examples/banner.png)

[![DOI](https://joss.theoj.org/papers/10.21105/joss.02318/status.svg)](https://doi.org/10.21105/joss.02318) 

[PyStokes](https://github.com/rajeshrinet/pystokes) is a numerical library for phoresis and Stokesian hydrodynamics in Python. The library has been specifically designed for studying phoretic and hydrodynamic interactions  in suspensions of active particles,  which are distinguished by their ability to produce flow, and thus motion, in the absence of external forces or torques.  Such particles are
endowed with a mechanism to produce hydrodynamic flow in a thin interfacial layer, which
may be due to the motion of cilia, as in microorganisms (Brennen & Winet, 1977) or osmotic
flows of various kinds in response to spontaneously generated gradients of phoretic fields
(Ebbens & Howse, 2010). The latter, often called autophoresis, is a generalisation of wellknown phoretic phenomena including, *inter alia*, electrophoresis (electric field), diffusiophoresis
(chemical field) and thermophoresis (temperature field) that occur in response to externally
imposed gradients of phoretic fields (Anderson, 1989).


Hydrodynamic and phoretic interactions between active particles in a viscous fluid are central to the understanding of their collective dynamics.  Under experimentally relevant conditions, the motion of the fluid is governed by the Stokes equation and that of the phoretic field, if one is present, by the Laplace equation.  The “activity” appears in these equations as boundary conditions on the particle surfaces that prescribe the slip velocity in the Stokes equation and flux of the phoretic field in the Laplace equation 

![Input and output structure of PyStokes to determine the hydrodynamic and phoretic interactions between active particles in a three-dimensional domain $V$. The equations are coupled by active boundary conditions on the surface $S_{i}$ of the particles. Particle indices are $i=1,\ldots,N$ and harmonic indices are $l=1,2,\ldots$ and $\sigma=s,a,t$ (see text). \label{fig:figS}](https://raw.githubusercontent.com/rajeshrinet/pystokes/master/docs/paper/FigSchema.png)


The slip velocity and the phoretic flux are related by a linear constitutive law that can be derived from a detailed analysis of the boundary layer physics (Anderson, 1989). The Stokes and Laplace equations are coupled by this linear constitutive law only at the particle boundaries. The linearity of the governing equations and the coupling boundary conditions allows for a formally exact solution of the problem of determining the force per unit area on the particle surfaces. This formally exact solution can be approximated to any desired degree of accuracy by a truncated series expansion in a complete basis of functions on the particle boundaries. This, in turn, leads to an efficient and accurate numerical method for computing hydrodynamic and phoretic interactions between active particles.


![Image](https://raw.githubusercontent.com/rajeshrinet/pystokes-examples/master/gallery/2_volvox.gif)
