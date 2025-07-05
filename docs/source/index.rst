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
      <img src="_static/images/von_mises.png" style="height: 200px; width: auto; object-fit: contain;" />
      <figcaption>Linear static analysis of a bracket.</figcaption>
   </figure>
   <figure style="margin: 0; text-align: center;">
      <img src="_static/images/to.gif" style="height: 200px; width: auto; object-fit: contain;" />
      <figcaption>Topology optimization with differentiable simulation.</figcaption>
   </figure>
   </div>

   <div style="display: flex; flex-direction: column; align-items: center;">
      <div style="display: flex; justify-content: center; gap: 60px; flex-wrap: wrap;">
         <img src="_static/images/stokes_u.png" style="height: 200px; width: auto; object-fit: contain;" />
         <img src="_static/images/stokes_p.png" style="height: 200px; width: auto; object-fit: contain;" />
      </div>
      <p style="text-align: center; margin-top: 10px;"><em>Stokes flow: velocity (left) and pressure(right).</em></p>
   </div>

   <div style="display: flex; flex-direction: column; align-items: center;">
      <div style="display: flex; justify-content: center; gap: 60px; flex-wrap: wrap;">
         <img src="_static/images/polycrystal_grain.gif" style="height: 260px; width: auto; object-fit: contain;" />
         <img src="_static/images/polycrystal_stress.gif" style="height: 260px; width: auto; object-fit: contain;" />
      </div>
      <p style="text-align: center; margin-top: 10px;"><em>Crystal plasticity: grain structure (left) and stress-xx (right).</em></p>
   </div>

   <div style="display: flex; flex-direction: column; align-items: center;">
      <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
         <img src="_static/images/ded.gif" style="height: 280px; width: auto; object-fit: contain;" />
      </div>
      <p style="text-align: center; margin-top: 10px;"><em>Thermal profile in direct energy deposition.</em></p>
   </div>

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

   