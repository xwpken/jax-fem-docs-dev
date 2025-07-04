.. jax-fem-docs documentation master file, created by
   sphinx-quickstart on Thu Jul  3 15:46:45 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to JAX-FEM's documentation!
===================================

.. Add your content using ``reStructuredText`` syntax. See the
.. `reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
.. documentation for details.

JAX-FEM is a GPU-accelerated differentiable finite element analysis package based on `JAX <https://github.com/google/jax>`_. Used to be part of the suite of open-source python packages for Additive Manufacturing (AM) research, `JAX-AM <https://github.com/tianjuxue/jax-am>`_.

.. raw:: html

   <div style="display: flex; justify-content: center; align-items: flex-start; gap: 20px;">
   <figure style="margin: 0; text-align: center;">
      <img src="images/von_mises.png" style="height: 200px; width: auto; object-fit: contain;" />
      <figcaption>Linear static analysis of a bracket.</figcaption>
   </figure>
   <figure style="margin: 0; text-align: center;">
      <img src="images/to.gif" style="height: 200px; width: auto; object-fit: contain;" />
      <figcaption>Topology optimization with differentiable simulation.</figcaption>
   </figure>
   </div>

   <p align="middle">
   <img src="images/stokes_u.png" width="260" />
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   <img src="images/stokes_p.png" width="260" />
   </p>
   <p align="middle">
      <em >Stokes flow: velocity (left) and pressure(right).</em>
   </p>

   <p align="middle">
   <img src="images/polycrystal_grain.gif" width="260" />
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   <img src="images/polycrystal_stress.gif" width="260" />
   </p>
   <p align="middle">
      <em >Crystal plasticity: grain structure (left) and stress-xx (right).</em>
   </p>

   <p align="middle">
   <img src="images/ded.gif" width="500" />
   </p>
   <p align="middle">
      <em >Thermal profile in direct energy deposition.</em>
   </p>

.. toctree::
   :maxdepth: 3  
   :caption: User Guide
   :hidden:

   Installation <user_guide/Installation>
   Quickstart <user_guide/Quickstart>
   
   Frequently asked questions (FAQ) <user_guide/FAQ/index>

.. toctree::
   :maxdepth: 2
   :caption: Learn by examples
   :hidden:

   Linear elasticity <examples/linear_elasticity>

   Hyperelasticity <examples/hyperelasticity>

   Inverse problem <examples/inverse>

   Plasticity <examples/plasticity>

   Topology optimization <examples/topology_optimization>

.. toctree::
   :maxdepth: 2
   :caption: More resources
   :hidden:

   Advanced examples <more/advanced>

   API reference <more/api>

   Change log <more/log>

   About the project <more/project>

   