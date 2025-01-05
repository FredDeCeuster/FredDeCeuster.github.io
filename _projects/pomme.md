---
layout: page
title: pomme
description: A modern software library for <br> 3D Radiative Transfer and <br> Synthetic Observations
img: assets/img/magritte.png
importance: 1
category: software
---

<strong>Magritte</strong> is an open-source software
library for simulating 3D radiation transport and synthetic observations,
developed at [University College London](https://www.ucl.ac.uk/) (UCL, UK)
and [KU Leuven](https://www.kuleuven.be/english/) (Belgium).

<ul>
    <li>
        The <strong>source code</strong> can be found at <strong><a href="https://github.com/Magritte-code/Magritte">github.com/Magritte-code/Magritte</a></strong>.
    </li>
    <li>
        The <strong>documentation</strong> can be found at <strong><a href="https://magritte.readthedocs.io/en/stable/">magritte.readthedocs.io</a></strong>.
    </li>
</ul>

Magritte is currently mainly used for post-processing hydrodynamical simulations by
creating synthetic observations, but the techniques could also be applied more general.
It can either be used as a Python package or as a C++ library.
Magritte uses a deterministic ray-tracer with a formal solver that currently focusses on
line radiative transfer (see
[De Ceuster et al. 2019](https://ui.adsabs.harvard.edu/abs/2020MNRAS.492.1812D/abstract)
for more details).

The plot below shows synthetic observations made with
Magritte at three different inclinations for a hydro simulation of the stellar wind around
an asymptotic giant branch (AGB) star as it is perturbed by a companion.

<video width="100%" controls playsinline autoplay muted loop>
  <source src="/assets/mov/movie.webm">
  Your browser does not support the video tag.
</video>

The hydrodynamics model was created by Jan Bolte using [MPI-AMRVAC](http://amrvac.org/). See
the [examples](https://magritte.readthedocs.io/en/stable/1_examples/index.html)
in the documentation to learn how these synthetic observations were created
with Magritte.
