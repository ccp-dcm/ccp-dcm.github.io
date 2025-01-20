.. ccp-dcm documentation master file, created by
   sphinx-quickstart on Mon Jan 20 12:43:07 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


.. image:: _static/firedrake.png
   :target: https://firedrakeproject.org
   :align: left
   :width: 15%

.. image:: _static/fenics_logo.png
   :target: https://fenicsproject.org
   :align: right
   :width: 15%

Towards a CCP on Data-centric Computational Mechanics
=====================================================

This is a `collaborative computational community
<https://www.ukri.org/opportunity/collaborative-computational-communities-towards-new-ccps/>`__
centred around the FEniCS and Firedrake finite element systems. `FEniCS
<https://fenicsproject.org>`__ and `Firedrake <https://firedrakeproject.org>`__
are world-leading software frameworks for the numerical solution of partial
differential equations (PDEs). These numerical simulations are essential for
advancing science and engineering across a very broad range of disciplines.
FEniCS and Firedrake are used to develop solvers in the geosciences (ocean,
atmosphere, cryosphere, geodynamics), nuclear fusion (plasma, tritium
transport, breeding blankets), physiology and medicine (brain, heart), and many
more besides.

Firedrake and FEniCS
--------------------

FEniCS and Firedrake are revolutionary packages that make it orders of
magnitude less expensive to develop sophisticated PDE solvers. Their unique
combination of mathematical software abstractions with code generation
techniques enables scientists and engineers to compose advanced
discretisations, scalable solvers, and adjoint techniques for systems modelled
by any PDE. By generating low-level assembly code from a high-level
description, the code can be aggressively optimised for the problem and
architecture at hand.

Some of our applications
------------------------

Scientists and engineers around the world use Firedrake and FEnICS for an
enormous range of simulation tasks. Here are just a few of the more prominent:

.. card-carousel:: 2

   .. card:: Weather and climate
      :link: https://www.firedrakeproject.org/gusto/

      .. figure:: _static/gusto_galewsky_3580_edit3.png

         `Gusto <https://www.firedrakeproject.org/gusto/>`__ uses Firedrake to
         prototype the dynamical core of the Met Office's next-generation
         numerical weather prediction and climate model.

   .. card:: Cerebral fluid flow
      :link: https://www.simula.no/research/projects/waterscales-mathematical-and-computational-foundations-modeling-cerebral-fluid

      .. figure:: _static/waterscales_streamlines_183_6h.png

         `Waterscales <https://www.simula.no/research/projects/waterscales-mathematical-and-computational-foundations-modeling-cerebral-fluid>`__ uses FEniCS to model fluid flow and solute transport in
         the brain, to better understand the need for sleep and the progression
         of neurodegenerative diseases.

   .. card:: Mantle convection
      :link: https://gadopt.org

      .. figure:: _static/gadopt_pacific_global_mantle_convection.png

         `G-ADOPT <https://gadopt.org>`__ simulates mantle convection.
         Firedrake's adjoint enables assimilation of tectonic plate motion to
         constrain the prior state of the Earth's interior.

   .. card:: Fusion power
      :link: https://festim.readthedocs.io/en/latest/

      .. figure:: _static/festim_wcll.png

         `FESTIM <https://festim.readthedocs.io/en/latest/>`__ uses FEniCS to
         simulate hydrogen transport and heat transfer processes. UKAEA use it
         to simulate tritium embrittlement of plasma-facing components for
         ITER.

Our Collaborative Computational Community
-----------------------------------------

CCP-DCM is a collaboration between Firedrake and FEniCS developers with STFC
and our software users across all fields of science and engineering. Our role
is to support and develop the core simulation toolchain to enable current and
new users to continue to push the limits of the possible in simulation scale.

.. toctree::
   :maxdepth: 2
   :caption: Contents:
