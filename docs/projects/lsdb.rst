HATS and LSDB
========================================================================================

Demonstration prepared for the MidPoint Review of LINCC Frameworks, Pittsburgh, 2025.
This demo showcases working with HATS-partitioned survey catalogs via LSDB.

Main references
---------------------------------------------------------------

* `Slide deck <https://docs.google.com/presentation/d/1l0f3MMwpsQUn4JFcAKxlYRQ5eVZrlKJKtWheTq-lRXU/>`__
* LSDB (`on GitHub <https://github.com/astronomy-commons/lsdb>`__) 
  (`on ReadTheDocs <https://lsdb.readthedocs.io/en/stable/>`__)
* HATS (`on GitHub <https://github.com/astronomy-commons/hats>`__)
  (`on ReadTheDocs <https://hats.readthedocs.io/en/stable/>`__)
* nested-dask (`on GitHub <https://github.com/lincc-frameworks/nested-dask>`__) 
  (`on ReadTheDocs <https://nested-dask.readthedocs.io/en/stable/>`__)
* nested-pandas (`on GitHub <https://github.com/lincc-frameworks/nested-pandas>`__) 
  (`on ReadTheDocs <https://nested-pandas.readthedocs.io/en/stable/>`__)


Getting Started 
---------------------------------------------------------------

You can follow along with this demo by creating your own local environment.

**Local installation**

If installing in your own hardware, create a virtual environment and install the relevant packages:

.. code-block:: bash

    >> conda create --name lincc python=3.12
    >> conda activate lincc
    >> pip install lsdb pyvo ipyaladin cesium scikit-learn aiohttp

Notebooks
---------------------------------------------------------------

:doc:`Notebook </notebooks/lsdb/Notebook_LSDB_HATS>`

In this notebook we will learn how to:

- Load object and source catalogs (lazily)
- Perform crossmatching with existing `LSDB` catalogs
- Save the results of a science workflow to disk

Acknowledgements
---------------------------------------------------------------

This project is supported by Schmidt Sciences.

This project is based upon work supported by the National Science Foundation under Grant No. AST-2003196.

This project acknowledges support from the DIRAC Institute in the Department of Astronomy at the University of Washington. The DIRAC Institute is supported through generous gifts from the Charles and Lisa Simonyi Fund for Arts and Sciences, and the Washington Research Foundation.
