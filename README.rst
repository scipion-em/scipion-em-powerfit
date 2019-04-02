=======================
Powerfit scipion plugin
=======================

Program from bonvinlab (http://www.bonvinlab.org/education/powerfit) for fitting a PDB into a 3D volume



- **TUTORIAL:** https://github.com/I2PC/scipion/wiki/User-Documentation#tutorials

- **TUTORIAL:** (from original developer): http://www.bonvinlab.org/education/powerfit/

=====
Setup
=====

- **Install this plugin:**

.. code-block::

    scipion installp -p scipion-em-powerfit

OR

  - through the plugin manager GUI by launching Scipion and following **Configuration** >> **Plugins**

Alternatively, in devel mode:

.. code-block::

    scipion installp -p local/path/to/scipion-em-powerfit --devel

- **TESTS:**
    - ./scipion test powerfit_scipion.tests.test_powerfit

![Builbot_URL]: http://heisenberg.cnb.csic.es:9980/#/builders/30

![alt text](http://heisenberg.cnb.csic.es:9980/badges/powerfit_devel.svg)

