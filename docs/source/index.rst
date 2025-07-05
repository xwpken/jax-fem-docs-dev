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
      <p style="margin-top: 10px;"><em>Linear static analysis of a bracket.</em></p>
   </figure>
   <figure style="margin: 0; text-align: center;">
      <img src="_static/images/to.gif" style="height: 200px; width: auto; object-fit: contain;" />
      <p style="margin-top: 10px;"><em>Topology optimization with differentiable simulation.</em></p>
   </figure>
   </div>

   <div style="display: flex; justify-content: center; align-items: flex-start; gap: 60px;">
      <figure style="margin: 0; text-align: center;">
         <img src="_static/images/stokes_u.png" style="height: 200px; width: auto; object-fit: contain;" />
      </figure>
      <figure style="margin: 0; text-align: center;">
         <img src="_static/images/stokes_p.png" style="height: 200px; width: auto; object-fit: contain;" />
      </figure>
   </div>
   <p style="text-align: center; margin-top: 10px;"><em>Stokes flow: velocity (left) and pressure(right).</em></p>


   <div style="display: flex; justify-content: center; align-items: flex-start; gap: 60px;">
      <figure style="margin: 0; text-align: center;">
         <img src="_static/images/polycrystal_grain.gif" style="height: 260px; width: auto; object-fit: contain;" />
      </figure>
      <figure style="margin: 0; text-align: center;">
         <img src="_static/images/polycrystal_stress.gif" style="height: 260px; width: auto; object-fit: contain;" />
      </figure>
   </div>
   <p style="text-align: center; margin-top: 10px;"><em>Crystal plasticity: grain structure (left) and stress-xx (right).</em></p>


   <div style="display: flex; justify-content: center; align-items: flex-start; gap: 20px;">
      <figure style="margin: 0; text-align: center;">
         <img src="_static/images/ded.gif" style="height: 280px; width: auto; object-fit: contain;" />
      </figure>
   </div>
   <p style="text-align: center; margin-top: 10px;"><em>Thermal profile in direct energy deposition.</em></p>

.. toctree::
   :maxdepth: 3  
   :caption: User Guide
   :hidden:

   Installation <guide/Installation>
   Quickstart <guide/Quickstart>
   
   Frequently asked questions (FAQ) <guide/FAQ/FAQ_main>

.. toctree::
   :maxdepth: 2
   :caption: Learn by examples
   :hidden:

   Linear elasticity <learn/linear_elasticity>

   Hyperelasticity <learn/hyperelasticity>

   Inverse problem <learn/inverse>

   Plasticity <learn/plasticity>

   Topology optimization <learn/topology_optimization>

.. toctree::
   :maxdepth: 2
   :caption: More resources
   :hidden:

   Advanced examples <more/advanced>

   API reference <more/api/api_main>

   Change log <more/log>

   About the project <more/project>

   