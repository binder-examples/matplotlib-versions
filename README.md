# Matplotlib versions example

This repo demonstrates how versions of Python packages can introduce significant changes to the execution of code that don't necessarily fail.

The upgrade of Matplotlib from version 1.x to 2.x changed the colour maps of the library.
This repo has two branches, one with Matplotlib v1.5.0 and another with Matplotlib v2.0.0.
The Jupyter Notebook `matplotlib_versions_demo.ipynb` is common to both of these branches and will demonstrate this difference caused by the version upgrade.

Launch the notebook with **Matplotlib v1.5.0**:

Launch the notebook with **Matplotlib v2.0.0**:

**NOTE:** Each version of Matplotlib has its own Numpy dependency which are different in this scenario.
