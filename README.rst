
Spikelib
========

A Python package for reading, manipulating, analyzing and visualize
spike sorted extracellular data. The spikelib was designed to give a
suite of tools that allow us to analyze spiketrains from multi-electrode
array (MEA) recordings obtained from some spike sorting software (for
example spiking-circus).

Installation
------------

Dependencies
~~~~~~~~~~~~

This is the list dependencies

.. code:: sh

   pip install numpy scipy matplotlib scikit-learn peakutils pandas h5py lmfit numpydoc

Optionally you can install neuroshare to read .mcd files. But it only
work on Python 2.7

.. code:: sh

   pip install neuroshare

Install
~~~~~~~

There are 2 ways to install spikelib, from Pypi or github. The easier
way is install using pip.

.. code:: sh

   pip install spikelib

Alternatively, you can install the latest version of spikelib from
github running the following commands:

.. code:: sh

   git clone https://github.com/creyesp/spikelib
   cd spikelib
   python setup.py [install, develop]

Where the develop argument should be used if you want to modify the
code.


Documentation
-------------
For more info and documentation, see the
`spikelib documentation <https://spikelib.readthedocs.io>`_.
