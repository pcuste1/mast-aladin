.. |stsci-logo| image:: docs/assets/mast-aladin-logo.svg
    :alt: STScI logo
    :height: 200px

|stsci-logo|

.. image:: https://github.com/spacetelescope/mast-aladin/actions/workflows/ci_workflows.yml/badge.svg
    :target: https://github.com/spacetelescope/mast-aladin/actions/workflows/ci_workflows.yml
    :alt: GitHub Actions CI Status

.. image:: https://readthedocs.org/projects/mast-aladin/badge/?version=latest
    :target: https://mast-aladin.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status



``mast-aladin`` adds convenience methods for visualizing and interacting with query results from MAST on the Aladin sky atlas, including queries for observations and sources in catalogs. 

``mast-aladin`` is a Python package maintained by the Space Telescope Science Institute that extends `ipyaladin <https://github.com/cds-astro/ipyaladin>`_, a package maintained by CDS (Centre de Données astronomiques de Strasbourg). ``ipyaladin`` is a Jupyter widget wrapper for `aladin-lite <https://github.com/cds-astro/aladin-lite>`_, also maintained by CDS.

Key Features
------------

- Runs in Jupyter notebooks locally or on the `Roman Research Nexus <https://roman.science.stsci.edu/>`_.
- Provides interactive access through the Aladin Lite interface and a Python API, with all-sky imaging from surveys including SDSS, Pan-STARRS, WISE, GALEX, and more.
- Visualizes and interacts with MAST observation and catalog query results. Includes plotting observation footprints and source catalog plotting tools, and works with `mast-table <https://github.com/spacetelescope/mast-table>`_ results.
- Integrates with `jdaviz <https://jdaviz.readthedocs.io/en/stable/>`_ through the AIDA (Astronomical Interactive Data Analysis) framework.

Documentation
-------------

`Click here to see the full documentation for mast-aladin 
on Read The Docs <https://mast-aladin.readthedocs.io/en/latest/>`_.