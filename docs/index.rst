BrainPy documentation
=====================

`BrainPy`_ is a highly flexible and extensible framework targeting on the
general-purpose Brain Dynamics Programming (BDP). Among its key ingredients, BrainPy supports:

- **JIT compilation** and **automatic differentiation** for class objects.
- **Numerical methods** for ordinary differential equations (ODEs),
  stochastic differential equations (SDEs),
  delay differential equations (DDEs),
  fractional differential equations (FDEs), etc.
- **Dynamics building** with the modular and composable programming interface.
- **Dynamics simulation** for various brain objects with parallel supports.
- **Dynamics training** with various machine learning algorithms,
  like FORCE learning, ridge regression, back-propagation, etc.
- **Dynamics analysis** for low- and high-dimensional systems, including
  phase plane analysis, bifurcation analysis, linearization analysis,
  and fixed/slow point finding.
- And more others ......


.. _BrainPy: https://github.com/brainpy/BrainPy


.. note::
   BrainPy is still an experimental research project.
   APIs may be changed over time. Please always keeps
   in mind what BrainPy version you are using.



.. toctree::
   :maxdepth: 1
   :caption: Quickstart

   quickstart/installation
   quickstart/simulation
   quickstart/training
   quickstart/analysis


.. toctree::
   :maxdepth: 1
   :caption: BrainPy Core Concepts

   core_concept/brainpy_transform_concept
   core_concept/brainpy_dynamical_system


.. toctree::
   :maxdepth: 2
   :caption: Brain Dynamics Tutorials

   tutorial_math/index
   tutorial_building/index
   tutorial_simulation/index
   tutorial_training/index
   tutorial_analysis/index


.. toctree::
   :maxdepth: 2
   :caption: Advanced Tutorials

   tutorial_advanced/math.rst
   tutorial_advanced/interoperation.rst
   tutorial_advanced/analysis.rst


.. toctree::
   :maxdepth: 1
   :caption: Toolboxes

   tutorial_toolbox/ode_numerical_solvers
   tutorial_toolbox/sde_numerical_solvers
   tutorial_toolbox/fde_numerical_solvers
   tutorial_toolbox/dde_numerical_solvers
   tutorial_toolbox/joint_equations
   tutorial_toolbox/synaptic_connections
   tutorial_toolbox/synaptic_weights
   tutorial_toolbox/optimizers
   tutorial_toolbox/saving_and_loading
   tutorial_toolbox/inputs


.. toctree::
   :maxdepth: 1
   :caption: Frequently Asked Questions

   tutorial_FAQs/citing_and_publication
   tutorial_FAQs/uniqueness_of-brainpy-math
   tutorial_FAQs/brainpy_ecosystem.ipynb


.. toctree::
   :maxdepth: 1
   :caption: API Documentation

   apis/auto/brainpy.rst
   apis/auto/math.rst
   apis/auto/dnn.rst
   apis/auto/dyn.rst
   apis/auto/integrators.rst
   apis/auto/analysis.rst
   apis/auto/connect.rst
   apis/auto/encoding.rst
   apis/auto/initialize.rst
   apis/auto/inputs.rst
   apis/auto/losses.rst
   apis/auto/measure.rst
   apis/auto/optim.rst
   apis/auto/running.rst
   apis/auto/mixin.rst
   apis/auto/changelog.rst


The following APIs will no longer be maintained in the future, but you can still use them normally.

.. toctree::
   :maxdepth: 1

   apis/channels.rst
   apis/neurons.rst
   apis/rates.rst
   apis/synapses.rst
   apis/synouts.rst
   apis/synplast.rst
   apis/layers.rst


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
